# Art Datasets for Machine Learning

A curated list of publicly available art datasets for machine learning research, covering classification, object detection, visual question answering, aesthetics, generative models, sketches, and more. Includes both scientific benchmark datasets and museum open-access collections.

Contributions welcome via pull request.

> **Availability:** ✅ freely downloadable (direct download, Zenodo, Kaggle, HuggingFace, GitHub, etc.)
> 📩 requires application or approval
> 📄 paper only, no public data link found
> 🔒 browse only, no bulk download

## Table of Contents

- [Research Datasets](#research-datasets)
  - [Classification, Style & Attribution](#classification-style--attribution)
  - [Object Detection, Pose & Iconography](#object-detection-pose--iconography)
  - [Aesthetics & Emotion](#aesthetics--emotion)
  - [Faces & Portraits in Art](#faces--portraits-in-art)
  - [Multimodal & Visual QA](#multimodal--visual-qa)
  - [Sketches & Drawings](#sketches--drawings)
  - [Forgery & Authentication](#forgery--authentication)
  - [Generative AI & Diffusion](#generative-ai--diffusion)
  - [Cartoon, Manga & Illustration](#cartoon-manga--illustration)
  - [Cultural Heritage & Archaeology](#cultural-heritage--archaeology)
  - [Street Art & Graffiti](#street-art--graffiti)
  - [Knowledge Graphs & Metadata](#knowledge-graphs--metadata)
- [Museum & Gallery Collections](#museum--gallery-collections)
- [Aggregated & Cross-Institution Datasets](#aggregated--cross-institution-datasets)
- [Related Resources](#related-resources)

---

## Research Datasets

Sorted by year (newest first) within each category.

### Classification, Style & Attribution

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| Stylebreeder | 6.8M images, 1.8M prompts | 2024 | ✅ | [paper](https://arxiv.org/abs/2406.14599), [huggingface](https://huggingface.co/datasets/stylebreeder/stylebreeder) | AI-generated images from Artbreeder with style clusters. NeurIPS 2024, CC0 |
| fruit-SALAD | 10,000 images | 2024 | ✅ | [paper](https://arxiv.org/abs/2406.01278), [code](https://github.com/Style-Aligned-Artwork-Datasets/fruit-SALAD) | Synthetic benchmark for style vs content similarity in embeddings |
| StyleBabel | 135,000 artworks | 2022 | 📄 | [paper (ECCV)](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680212.pdf) | Free-form style tags and captions from art/design students on Behance |
| ArtBench-10 | 60,000 images | 2022 | ✅ | [paper](https://arxiv.org/abs/2206.11404), [code](https://github.com/liaopeiyuan/artbench), [kaggle](https://www.kaggle.com/datasets/alexanderliao/artbench10) | Class-balanced benchmark, 10 styles, clean annotations |
| WikiArtVectors | 68,094 artworks | 2022 | 📄 | [paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9497612/) | Precomputed CLIP embeddings for WikiArt, 132 styles |
| DELAUNAY | 11,503 images | 2022 | ✅ | [paper](https://arxiv.org/abs/2201.12123), [code](https://github.com/camillegontier/DELAUNAY_dataset) | Abstract and non-figurative art, 53 artists |
| contempArt | 14,398 images, 441 artists | 2020 | ✅ | [paper](https://arxiv.org/abs/2008.09558), [zenodo](https://doi.org/10.5281/zenodo.19365430), [github](https://github.com/georgeblck/contempart) | Contemporary art from German art schools with social network data (456K edges) and demographics |
| DomainNet | 600,000 images | 2019 | ✅ | [website](https://ai.bu.edu/M3SDA/) | 345 classes across 6 domains (painting, clipart, sketch, photo, etc.) |
| NoisyArt | 90,000+ images | 2019 | ✅ | [paper](https://www.scitepress.org/Papers/2019/73927/), [code](https://github.com/delchiaro/NoisyArt) | Webly-supervised artwork recognition with noisy web labels, 3,000+ classes |
| Multitask Painting Collection | ~100,000 images | 2019 | ✅ | [paper](https://arxiv.org/pdf/1812.08052.pdf), [data](http://www.ivl.disco.unimib.it/activities/paintings/) | Multitask learning: artist, style, genre, period |
| Best Artworks of All Time | ~8,000 images | 2019 | ✅ | [kaggle](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time) | 50 most influential artists, popular starter dataset |
| BAM! | 2.5M+ images | 2017 | 📄 | [paper](https://arxiv.org/abs/1704.08614) | Behance Artistic Media: content, emotion, and media labels. ICCV 2017 |
| Art 500K | ~500,000 images | 2017 | 📄 | [paper](https://dl.acm.org/doi/pdf/10.1145/3123266.3123405), ~~[data](http://deepart2.ece.ust.hk/ART500K/art500k.html)~~ | Large-scale art retrieval. Download link dead (404 as of 2026-04). Compiled from WikiArt + WGA + Rijks + Google Arts |
| Pandora 18k | 18,038 images | 2016 | 📄 | [paper](https://arxiv.org/abs/1602.08855) | 18 art styles, expert-labeled, higher annotation quality than WikiArt |
| Painter by Numbers | 103,250 images | 2016 | ✅ | [kaggle](https://www.kaggle.com/c/painter-by-numbers) | Kaggle competition: predict whether two paintings are by the same artist |
| Rijksmuseum Challenge | 112,039 images (3,593 paintings) | 2014 | ✅ | [paper](https://dl.acm.org/doi/pdf/10.1145/2578726.2578791), [data](https://figshare.com/articles/Rijksmuseum_Challenge_2014/5660617), [code](https://github.com/tmensink/rijkschallenge) | Artist, material, type prediction |
| Painting-91 | 4,266 images | 2014 | ✅ | [paper](https://link.springer.com/article/10.1007/s00138-014-0621-6), [data](http://www.cat.uab.cat/~joost/painting91.html) | 91 painters, style classification |
| PRINTART | 988 images | 2012 | ✅ | [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-642-33765-9_11.pdf), [data](http://printart.isr.ist.utl.pt/database.html) | Print art classification |
| WikiArt | ~250,000 images | ✅ | varies | [website](https://www.wikiart.org/), [crawler](https://github.com/lucasdavid/wikiart), [source 1](https://github.com/rkjones4/GANGogh), [source 2](https://github.com/cs-chan/ArtGAN/tree/master/WikiArt%20Dataset), [kaggle](https://www.kaggle.com/datasets/steubk/wikiart) | 3,000+ artists, most widely used art dataset. API signups currently disabled |
| WikiArt 215K (HuggingFace) | 215,000 images | ✅ | varies | [huggingface](https://huggingface.co/datasets/matrixglitch/wikiart-215k) | Preprocessed WikiArt with image URLs and captions (title, artist, year, genre, style). 150K+ with parseable dates |
| Web Gallery of Art | ~19,000 images | ongoing | ✅ | [website](https://www.wga.hu/index1.html) | European fine art, encyclopedic scope |

### Object Detection, Pose & Iconography

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| Poses of People in Art | 2,454 images, 10,749 figures | 2024 | ✅ | [paper](https://dl.acm.org/doi/10.1145/3696455), [data](https://zenodo.org/records/7516230) | First openly licensed pose estimation dataset for art, 22 depiction styles |
| Human-Art | 50,000 images, 123,000 person instances | 2023 | 📩 | [paper](https://arxiv.org/abs/2303.02760), [website](https://idea-research.github.io/HumanArt/) | Natural and artificial scenes (paintings, cartoons, sculptures). CVPR 2023 |
| DEArt | 15,000+ images | 2022 | ✅ | [paper](https://arxiv.org/abs/2211.01226), [data](https://zenodo.org/records/6984525) | 69 object classes, 12 pose categories, European paintings 12th-18th c. |
| ArtDL 2.0 | 42,479 images | 2021 | ✅ | [paper](https://dl.acm.org/doi/abs/10.1145/3458885), [data](https://artdl.org/), [code](https://github.com/iFede94/ArtDL) | Iconographic classification, 19 Iconclass classes, Renaissance art |
| Materials In Paintings | 19,325 paintings, 227,810 bboxes | 2021 | ✅ | [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0255109), [data](https://materialsinpaintings.tudelft.nl/) | Material perception (fabric, metal, wood, etc.) with fine-grained labels |
| IconArt | 5,955 images | 2018 | ✅ | [paper](https://arxiv.org/abs/1810.02569), [huggingface](https://huggingface.co/datasets/NGonthier/IconArt), [data](https://zenodo.org/records/4737435) | Weakly supervised iconographic element detection (angels, saints, etc.) |
| People-Art | images from 41 art movements | 2016 | ✅ | [paper](https://arxiv.org/abs/1610.08871), [code](https://github.com/BathVisArtData/PeopleArt) | Cross-depiction person detection across photos, cartoons, art |
| Oxford VGG Paintings | 210,000+ paintings (10K annotated) | 2014 | ✅ | [paper](https://www.robots.ox.ac.uk/~vgg/publications/2014/Crowley14/crowley14.pdf), [data](https://www.robots.ox.ac.uk/~vgg/data/paintings/) | Object retrieval in paintings, crowdsourced object tags |

### Aesthetics & Emotion

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| ArtELingo-28 | ~200,000 annotations, 28 languages | 2024 | 📄 | [paper](https://aclanthology.org/2024.emnlp-main.1165/) | Multilingual art emotion annotations. EMNLP 2024 |
| APDDv2 | 10,023 images, 85,191 scores | 2024 | ✅ | [paper](https://arxiv.org/abs/2411.08545), [code](https://github.com/BestiVictory/APDDv2) | Expert aesthetic scores and language comments, 10 attributes. NeurIPS 2024 |
| BAID | 60,337 images, 360,000+ votes | 2023 | ✅ | [paper](https://arxiv.org/abs/2303.15166), [code](https://github.com/Dreemurr-T/BAID) | BoldBrush artistic image aesthetics with user votes. CVPR 2023 |
| ArtELingo | ~1.24M annotations (EN/AR/ZH/ES) | 2022 | ✅ | [paper](https://aclanthology.org/2022.emnlp-main.600/), [website](https://www.artelingo.org/) | Multilingual emotion annotations on WikiArt. EMNLP 2022 |
| ArtEmis v2 | 260,000 contrastive instances | 2022 | ✅ | [website](https://www.artemisdataset-v2.org/) | Contrastive extension balancing positive/negative emotion pairs |
| TAD66K | 66,000 images, 47 themes | 2022 | ✅ | [paper](https://www.ijcai.org/proceedings/2022/132), [huggingface](https://huggingface.co/datasets/Shuai1995/TAD66K_for_Image_Aesthetics_Assessment) | Theme-oriented aesthetics, 1,200+ annotations per image. IJCAI 2022 |
| ArtEmis | 455,000 annotations on 80,000 artworks | 2021 | ✅ | [paper](https://arxiv.org/abs/2101.07396), [website](https://www.artemisdataset.org/) | Emotion attributions + verbal explanations for WikiArt. CVPR 2021 |
| WikiArt Emotions | 4,105 images, 20 emotion categories | 2018 | ✅ | [paper](https://aclanthology.org/L18-1197/), [data](http://saifmohammad.com/WebPages/wikiartemotions.html) | Crowdsourced emotions across four Western art periods |
| AVA | 250,000+ images | 2012 | ✅ | [paper](https://refbase.cvc.uab.es/files/MMP2012a.pdf), [kaggle](https://www.kaggle.com/datasets/nicolacarrassi/ava-aesthetic-visual-assessment) | Photography aesthetics from DPChallenge, scores + style labels |

### Faces & Portraits in Art

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| WikiArt Face | 6,095 face images | 2021 | ✅ | [data](https://asahiushio.com/projects/wikiart_face/), [code](https://github.com/asahi417/wikiart-image-dataset) | Faces cropped from portraits across art movements |
| AAHQ | ~25,000 images | 2021 | ✅ | [code](https://github.com/onion-liu/aahq-dataset) | Artistic portrait faces from Artstation, various painting styles |
| MetFaces | 1,336 face images (1024x1024) | 2020 | ✅ | [code](https://github.com/NVlabs/metfaces-dataset) | Faces from Met artworks, aligned and cropped for GAN training |
| Artistic Faces Dataset | from 103,250 artworks | 2019 | ✅ | [website](https://faculty.runi.ac.il/arik/site/foa/artistic-faces-dataset.asp) | 68 facial landmarks plus artist/style metadata |

### Multimodal & Visual QA

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| CognArtive | LLM art analyses | 2025 | ✅ | [paper](https://arxiv.org/abs/2502.04353), [website](https://cognartive.github.io/) | LLM-generated formal art analyses and aesthetic descriptions |
| MELArt | annotations over Wikimedia art | 2024 | ✅ | [paper](https://drops.dagstuhl.de/entities/document/10.4230/TGDK.2.2.8), [code](https://github.com/HPI-Information-Systems/MELArt) | Multimodal entity linking in paintings |
| AQUA | QA pairs over SemArt | 2020 | ✅ | [paper](https://arxiv.org/abs/2008.12520), [code](https://github.com/noagarcia/ArtVQA) | Visual and knowledge-based question answering on art |
| Artpedia | 2,930 paintings | 2019 | 📄 | [paper](https://link.springer.com/chapter/10.1007/978-3-030-30645-8_66) | 28,212 text sentences (visual + contextual), cross-modal retrieval |
| OmniArt | 2,050,017 images | 2018 | 📄 | [paper](https://dl.acm.org/doi/10.1145/3273022), ~~[data](http://isis-data.science.uva.nl/strezoski/#3)~~ | Multi-task, multi-label, metadata-rich. Download links dead (as of 2026-04). Compiled from Rijks + Met + WGA |
| SemArt | 21,383 images | 2018 | ✅ | [paper](http://noagarciad.com/docs/VISART2018.pdf), [data](http://noagarciad.com/SemArt/) | Semantic art descriptions paired with images |

### Sketches & Drawings

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| Creative Birds / Creatures | 10,000 sketches each | 2021 | ✅ | [paper](https://arxiv.org/abs/2011.10039), [code](https://github.com/facebookresearch/DoodlerGAN) | Part-annotated creative sketch datasets. ICLR 2021 |
| ImageNet-Sketch | 50,000 images, 1,000 classes | 2019 | ✅ | [code](https://github.com/HaohanWang/ImageNet-Sketch), [kaggle](https://www.kaggle.com/datasets/wanghaohan/imagenetsketch) | Sketch versions of ImageNet classes for domain shift evaluation |
| OpenSketch | 400+ sketches, 12 objects | 2019 | ✅ | [paper](https://dl.acm.org/doi/10.1145/3355089.3356533), [website](https://ns.inria.fr/d3/OpenSketch/) | Product design sketches from professional designers |
| SketchyScene | 29,056 scene sketches | 2018 | ✅ | [paper (ECCV)](https://openaccess.thecvf.com/content_ECCV_2018/papers/Changqing_Zou_SketchyScene_Richly-Annotated_Scene_ECCV_2018_paper.pdf), [website](https://sketchyscene.github.io/SketchyScene/) | Scene-level sketches with instance annotations |
| Quick, Draw! | 50M drawings, 345 categories | 2017 | ✅ | [website](https://quickdraw.withgoogle.com/data), [code](https://github.com/googlecreativelab/quickdraw-dataset), [huggingface](https://huggingface.co/datasets/google/quickdraw) | Google crowd-sourced sketch game, CC BY 4.0 |
| Sketchy Database | 75,471 sketches of 12,500 objects | 2016 | ✅ | [paper](https://dl.acm.org/doi/10.1145/2897824.2925954), [website](https://sketchy.eye.gatech.edu/) | First large-scale paired sketch-photo dataset. SIGGRAPH 2016 |
| TU-Berlin Sketches | 20,000 sketches, 250 categories | 2012 | ✅ | [huggingface](https://huggingface.co/datasets/sdiaeyu6n/tu-berlin) | Human sketches for sketch recognition research |

### Forgery & Authentication

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| Van Gogh Authentication | 338+ images | 2024 | ✅ | [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0295967), [data](https://zenodo.org/records/10276928) | Originals, human forgeries, and AI-generated fakes |
| DeepfakeArt Challenge | 32,000+ image pairs | 2023 | ✅ | [paper](https://arxiv.org/abs/2306.01272), [kaggle](https://www.kaggle.com/datasets/danielmao2019/deepfakeart), [code](https://github.com/h-aboutalebi/DeepfakeArt) | AI art forgery and data poisoning detection benchmark |

### Generative AI & Diffusion

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| Danbooru2023 | 5M+ images, 162M+ tags | 2023 | ✅ | [data (2021)](https://gwern.net/danbooru2021), [huggingface (2023)](https://huggingface.co/datasets/nyanko7/danbooru2023) | Crowdsourced anime/illustration, ~30 tags per image |
| CommonCanvas | ~70M CC images | 2023 | ✅ | [paper](https://arxiv.org/abs/2310.16825), [models](https://huggingface.co/common-canvas/CommonCanvas-XL-C) | Copyright-safe training data for diffusion models. CVPR 2024 |
| TWIGMA | 800,000+ images | 2023 | ✅ | [paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/769b70d1a9a6b21af53c00d0b322c763-Abstract-Datasets_and_Benchmarks.html), [data](https://zenodo.org/records/8031785) | AI-generated images from Twitter with metadata. NeurIPS 2023 |
| Pick-a-Pic | 1M+ preference pairs | 2023 | ✅ | [paper](https://arxiv.org/abs/2305.01569), [huggingface](https://huggingface.co/datasets/yuvalkirstain/pickapic_v1) | Human preferences for text-to-image, used for RLHF |
| JourneyDB | 4,429,295 images | 2023 | ✅ | [paper](https://arxiv.org/abs/2307.00716), [data](https://journeydb.github.io/), [huggingface](https://huggingface.co/datasets/JourneyDB/JourneyDB) | Midjourney images with prompts, captions, VQA. NeurIPS 2023 |
| AI-ArtBench | 185,015 images | 2023 | ✅ | [data (IEEE)](https://ieee-dataport.org/documents/ai-artbench), [kaggle](https://www.kaggle.com/datasets/ravidussilva/real-ai-art) | 60K human + 125K AI-generated, real vs AI art detection |
| Art-fm | 650K art images (training set) | 2025 | 📄 | [paper](https://arxiv.org/abs/2503.19527), [code](https://github.com/CompVis/fm-boosting) | Flow matching for art generation trained on 650K curated images (WikiArt + 7 museum sources, SSCD-deduped from 950K). LMU Munich, ICCV 2025 |
| SCFlow | N/A (model only) | 2025 | ✅ | [paper](https://arxiv.org/abs/2312.03478), [code](https://github.com/CompVis/SCFlow) | Style/content disentanglement via conditional flow matching in CLIP space. Same lab as Art-fm. ICCV 2025 |
| LAION-Aesthetics | ~120M images (score >7) | 2022 | ✅ | [info](https://laion.ai/blog/laion-aesthetics/), [data](https://github.com/LAION-AI/laion-datasets/blob/main/laion-aesthetic.md) | Aesthetic-filtered subset of LAION-5B, used to train Stable Diffusion v1 |
| DiffusionDB | 14M images, 1.8M prompts | 2022 | ✅ | [paper](https://arxiv.org/abs/2210.14896), [code](https://github.com/poloclub/diffusiondb), [huggingface](https://huggingface.co/datasets/poloclub/diffusiondb) | Stable Diffusion prompt-image pairs from Discord |
| COYO-700M | 747M image-text pairs | 2022 | ✅ | [data](https://github.com/kakaobrain/coyo-dataset) | Large-scale image-text pairs, CC-BY-4.0 |

### Cartoon, Manga & Illustration

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| iCartoonFace | 389,678 images, 5,013 characters | 2020 | 📄 | [paper](https://arxiv.org/abs/1907.13394) | Large-scale cartoon face detection and recognition |
| Manga109 | 109 volumes, 21,142 pages | 2020 | 📩 | [paper](https://arxiv.org/abs/2005.04425) | Japanese manga with annotated frames, faces, text, and characters |

### Cultural Heritage & Archaeology

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| CULTURE3D | 41,006 drone images, 20 sites | 2025 | ✅ | [paper](https://arxiv.org/abs/2501.06927), [code](https://github.com/openinterx/culture3d) | Cultural landmarks 3D reconstruction (pyramids, Forbidden City, etc.) |
| ARTeFACT | 445 images, 11,000+ annotations | 2024 | ✅ | [paper](https://arxiv.org/abs/2412.04580), [huggingface](https://huggingface.co/datasets/danielaivanova/damaged-media) | Pixel-level damage segmentation benchmark. 15 damage classes (i.e. cracks, dirt, material loss), 10 substrate materials, 4 content types, 20 media types (i.e. paintings, frescoes, manuscripts, mosaics, photographs). AFL-3.0 |
| MuralDH | 5,000+ images | 2024 | ✅ | [paper](https://www.nature.com/articles/s41597-024-03785-0), [code](https://github.com/tearsheaven/MuralDH) | Dunhuang mural restoration: segmentation, inpainting, super-resolution |
| WikiScenes | landmark photo collections | 2021 | ✅ | [code](https://github.com/tgxs002/wikiscenes) | Architectural landmarks with captions and 3D geometry. ICCV 2021 |
| ArchAIDE | 435 sketches, 381 photos | 2020 | 📄 | [paper](https://www.sciencedirect.com/science/article/abs/pii/S2352409X20305794) | Archaeological pottery classification via shape and decoration |

### Street Art & Graffiti

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| 17K-Graffiti | ~17,000 images | 2022 | ✅ | [code](https://github.com/visual-ds/17K-Graffiti) | Graffiti classification. VISAPP 2022 |

### Knowledge Graphs & Metadata

| Dataset | Size | Year | Avail. | Links | Notes |
|---------|------|------|--------|-------|-------|
| PainterPalette | ~10,000 painters | 2023 | ✅ | [code](https://github.com/me9hanics/PainterPalette) | WikiArt + Art500k + Wikidata painter metadata, network analysis |
| ArtGraph | 135,038 resources, 875,416 facts | 2022 | ✅ | [paper](https://arxiv.org/abs/2105.15028), [data](https://zenodo.org/records/6337958) | Knowledge graph linking WikiArt and DBpedia |

---

## Museum & Gallery Collections

Open-access collections from cultural institutions. Sorted by collection size (largest first) where size is known, then alphabetically for collections without published counts.

### Large Collections (100,000+ objects)

| Collection | Size | Avail. | License | Links | Notes |
|------------|------|--------|---------|-------|-------|
| Smithsonian Open Access | 11M+ records, 2.8M+ images | ✅ | CC0 | [github](https://github.com/Smithsonian/OpenAccess), [website](https://www.si.edu/openaccess), [AWS](https://registry.opendata.aws/smithsonian-open-access/) | 19 museums + research centers |
| Victoria and Albert Museum | 1M+ records, 500,000+ images | ✅ | personal/educational | [API](http://developers.vam.ac.uk/) | Decorative arts, fashion, design. IIIF, OpenAPI spec |
| Te Papa (New Zealand) | 1M+ objects, 200,000+ downloadable | ✅ | CC varies | [website](https://collections.tepapa.govt.nz/) | First Australasian large-scale open access museum |
| Rijksmuseum | 800,000+ objects | ✅ | CC0 (public domain works) | [data portal](https://data.rijksmuseum.nl/) | API and bulk downloads, high-resolution images |
| Louvre | 500,000+ works | ✅ | varies | [website](https://collections.louvre.fr/en/), [JSON docs](https://collections.louvre.fr/en/page/documentationJSON) | Append .json to any artwork URL. CSV export of searches |
| The Metropolitan Museum of Art | 470,000+ artworks | ✅ | CC0 | [github](https://github.com/metmuseum/openaccess) | Comprehensive metadata CSV, regularly updated |
| iMet Collection | 375,000 images | ✅ | varies | [paper](https://arxiv.org/pdf/1906.00901.pdf), [kaggle](https://www.kaggle.com/c/imet-2019-fgvc6/overview) | Fine-grained attribute recognition challenge |
| Cooper Hewitt | 215,000+ objects | ✅ | CC0 | [github](https://github.com/cooperhewitt/collection), [API](https://collection.cooperhewitt.org/api/) | Smithsonian design museum, JSON per object |
| Paris Musees | 150,000+ images | ✅ | CC0 | [website](http://parismuseescollections.paris.fr/en), [API](https://apicollections.parismusees.paris.fr/) | 14 Paris city museums. GraphQL API with free account (session cookie auth). ~8K paintings + ~63K drawings with dates and images |
| National Gallery of Art (DC) | 130,000+ artworks | ✅ | CC0 | [github](https://github.com/NationalGalleryOfArt/opendata) | CSV format with Wikidata identifiers |

### Medium Collections (10,000-100,000 objects)

| Collection | Size | Avail. | License | Links | Notes |
|------------|------|--------|---------|-------|-------|
| SMK (National Gallery of Denmark) | 88,000+ works | ✅ | CC0 | [API](https://api.smk.dk/api/v1/docs), [website](https://open.smk.dk/) | Leading OpenGLAM institution |
| National Palace Museum (Taiwan) | 70,000+ digitized images | ✅ | open gov | [data](https://theme.npm.edu.tw/opendata/?lang=2) | Chinese art, calligraphy, ceramics, bronzes. IIIF compliant |
| Yale Center for British Art | ~70,000 IIIF images | ✅ | public domain | [website](https://britishart.yale.edu/collections-data-sharing) | Linked Open Data via RDF |
| Cleveland Museum of Art | 61,000+ artworks | ✅ | CC0 | [github](https://github.com/ClevelandMuseumArt/openaccess), [API](https://www.clevelandart.org/open-access-api) | CSV and JSON data plus public API |
| Museo del Prado | ~40,000 artworks | ✅ | non-commercial | [knowledge graph](https://www.museodelprado.es/en/grafo-de-conocimiento/el-prado-en-la-web) | Linked Open Data, SPARQL-queryable |
| Finnish National Gallery | 36,000+ artworks | ✅ | CC0 | [github](https://github.com/hugovk/finnishnationalgallery) | Ateneum, Kiasma, Sinebrychoff collections |
| Getty Museum | 30,000+ high-res images | ✅ | no known restrictions | [website](https://www.getty.edu/projects/open-data-apis/) | Open Content Program, IIIF access |
| Whitney Museum | 17,000+ works | ✅ | CC0 | [github](https://github.com/whitneymuseum/open-access), [API](https://whitney.org/about/website/api) | CSV updated nightly. 20th/21st century American art |
| Williams College Museum of Art | ~15,600 records | ✅ | CC0 | [github](https://github.com/wcmaart/collection) | CSV format with thumbnails |
| Walters Art Museum | 10,000+ records | ✅ | CC0 | [github](https://github.com/WaltersArtMuseum/api-thewalters-org) | Static data files (API v1 retired 2023) |

### API / Full Collection Access (size unspecified)

| Collection | Avail. | License | Links | Notes |
|------------|--------|---------|-------|-------|
| Art Institute of Chicago | ✅ | CC0 | [github](https://github.com/art-institute-of-chicago/api-data), [API](http://api.artic.edu/docs/), [website](https://www.artic.edu/open-access) | REST API + bulk JSON dumps on AWS S3 |
| Harvard Art Museums | ✅ | varies | [API docs](https://github.com/harvardartmuseums/api-docs), [website](https://harvardartmuseums.org/collections/api) | REST API refreshed daily, IIIF-compatible |
| Minneapolis Institute of Art | ✅ | CC0 | [github](https://github.com/artsmia/collection) | JSON metadata, updated approximately daily |
| Brooklyn Museum | 📩 | varies | [API](https://www.brooklynmuseum.org/opencollection/api), [examples](https://github.com/brooklynmuseum/brooklynmuseum-api-examples) | REST API, registration required |
| British Museum | ✅ | non-commercial | [website](https://www.britishmuseum.org/collection/collection-online/guide), [github](https://github.com/britishmuseum) | SPARQL/Linked Data. Export up to 10K records per search |
| National Gallery (London) | ✅ | CC BY-NC-ND 4.0 | [API](https://data.ng-london.org.uk/) | ~2,300 paintings. Elasticsearch-based API |
| ColBase (National Museums of Japan) | ✅ | varies | [website](https://colbase.nich.go.jp/?locale=en) | Tokyo, Kyoto, Nara, Kyushu national museums |
| Science Museum Group (UK) | ✅ | CC varies | [API](https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api), [github](https://github.com/TheScienceMuseum/collectionsonline) | JSON/CSV exports, 37 GitHub repos |
| Auckland War Memorial Museum | ✅ | CC varies | [API](https://api.aucklandmuseum.com/) | API plus Linked Open Data |
| QAGOMA (Queensland, Australia) | ✅ | CC varies | [data](https://collection.qagoma.qld.gov.au/page/open-data) | CSV, refreshed monthly. Australian and Asia-Pacific art |

### Metadata Only / Limited Access

| Collection | Avail. | License | Links | Notes |
|------------|--------|---------|-------|-------|
| MoMA Collection | ✅ | varies | [github](https://github.com/MuseumofModernArt/collection) | Artist, artwork, exhibition data. Artworks.csv (via LFS) includes ImageURL column with direct JPEG links for ~64K works |
| Carnegie Museum of Art | ✅ | CC0 | [github](https://github.com/cmoa/collection) | Pittsburgh collection metadata |
| The Tate Collection | ✅ | CC-BY-NC-ND 3.0 | [github](https://github.com/tategallery/collection) | Metadata CSV includes thumbnail URLs. Images downloadable via CDN (swap _8.jpg for _10.jpg for 1536px). ~38K paintings/drawings with dates |
| Nationalmuseum Sweden | ✅ | CC0 | [github](https://github.com/NationalmuseumSWE/WikidataCollection) | Wikidata-linked metadata |
| ArtUK | 🔒 | restricted | [website](https://artuk.org/) | UK public art, browsable only. MDS extract API exists but aggressive bot protection (403 on all programmatic access, including Selenium, as of 2026-04) |

---

## Aggregated & Cross-Institution Datasets

| Dataset | Size | Avail. | License | Links | Notes |
|---------|------|--------|---------|-------|-------|
| Europeana | 50M+ cultural heritage objects | ✅ | varies | [data](https://pro.europeana.eu/page/harvesting-and-downloads) | Aggregator across thousands of European institutions |
| Wikidata: Sum of All Paintings | hundreds of thousands of paintings | ✅ | CC0 | [project](https://www.wikidata.org/wiki/Wikidata:WikiProject_sum_of_all_paintings) | Structured data linking paintings across museums. SPARQL queryable |
| art-museums-pd-440k | ~440,000 images | ✅ | CC-BY-4.0 | [huggingface](https://huggingface.co/datasets/Mitsua/art-museums-pd-440k) | Public domain museum art with bilingual captions, WebDataset format |

---

## Related Resources

- [awesome-openaccess-glam](https://github.com/micahwalterstudio/awesome-openaccess) - Curated list of museum open access projects
- [museums-on-github](https://github.com/Ambrosiani/museums-on-github) - List of museums with GitHub accounts
- [GLAM Workbench](https://glam-workbench.net/) - Tools and pre-harvested datasets from GLAM institutions
- [Museum APIs wiki](http://museum-api.pbworks.com/w/page/21933420/Museum%C2%A0APIs) - Comprehensive list of museum APIs
- [Awesome Machine Learning Art](https://github.com/vibertthio/awesome-machine-learning-art) - Tools and projects (not datasets)
- [Digital Art History Directory](https://dahd.hcommons.org/open-data-collections/) - Open data collections for art history
- [Hugging Face "art" datasets](https://huggingface.co/datasets?search=art) - Searchable hub
- [BigLAM on Hugging Face](https://huggingface.co/biglam) - GLAM datasets from the BigScience project
