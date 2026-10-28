# Paddy Land Watch

Everything needed to start on this topic.

| File | What it is |
|---|---|
| [paddy-land-watch.pdf](paddy-land-watch.pdf) | The full proposal (11 pages) |
| [brief-paddy-land-watch.pdf](brief-paddy-land-watch.pdf) | The one-page brief |
| [reading-notes-paddy-land-watch.pdf](reading-notes-paddy-land-watch.pdf) | The 10 related papers explained in simple words. Short on time? Read papers 4, 6 and 1. |
| [papers/](papers/) | 8 of the 10 papers. The numbers in the file names match the reading notes. |
| [presentation/paddy-land-watch-proposal-talk.pdf](presentation/paddy-land-watch-proposal-talk.pdf) | The proposal talk, 12 slides (28 Oct 2026): the problem, past research, users, the four land states, one slide per member (data analysis and technical work), the system, data, targets and links |
| [presentation/paddy-land-watch-proposal-talk.pptx](presentation/paddy-land-watch-proposal-talk.pptx) | The same talk as PowerPoint, to edit (no speaker notes) |

## The 10 papers

| # | Paper | In `papers/`? | Source |
|---|---|---|---|
| 1 | Weerasinghe et al. 2025: paddy land loss in Gampaha (preprint) | Yes | [Research Square](https://www.researchsquare.com/article/rs-7301248/v1) |
| 2 | Gunatilake et al. 2026: wetland loss in Colombo | Yes | [doi.org/10.3390/biosphere2030008](https://doi.org/10.3390/biosphere2030008) |
| 3 | Jayasooriya et al. 2023: the Southern Expressway and paddy loss | **Missing** | [KDU repository](https://ir.kdu.ac.lk/handle/345/7331) |
| 4 | Özdoğan et al. 2025: rice maps for every season in Sri Lanka | Yes | [doi.org/10.3390/rs17173065](https://doi.org/10.3390/rs17173065) |
| 5 | Sankavi et al. 2025: CNN paddy detection in the North Central Province | Yes | [UoM repository](https://dl.lib.uom.lk/handle/123/25014) |
| 6 | Shen & Liao 2025: Sentinel-1 rice maps on Hainan Island | Yes | [doi.org/10.3390/rs17061033](https://doi.org/10.3390/rs17061033) |
| 7 | Onojeghuo et al. 2023: ResU-Net with Sentinel-1 and Sentinel-2 | Yes | [doi.org/10.3390/rs15061517](https://doi.org/10.3390/rs15061517) |
| 8 | Kasture et al. 2025: abandoned paddy from radar (EGU slides) | **Missing** | [EGU abstract](https://meetingorganizer.copernicus.org/EGU25/EGU25-18606.html) |
| 9 | Brown et al. 2022: Dynamic World | Yes | [doi.org/10.1038/s41597-022-01307-4](https://doi.org/10.1038/s41597-022-01307-4) |
| 10 | Brown et al. 2025: AlphaEarth Foundations | Yes | [arxiv.org/abs/2507.22291](https://arxiv.org/abs/2507.22291) |

**The two missing papers**
- **Paper 3:** the KDU site blocks download scripts, but it works in a normal browser. Open the source link, save the PDF, and add it to `papers/` as `03 - 2023 - Jayasooriya - Southern Expressway and paddy loss.pdf`.
- **Paper 8:** the slides are only for people who registered for EGU 2025. The abstract on the source link is free to read.

## Code to look at

| Repo | What it gives us | Licence |
|---|---|---|
| [ozdogan15/srilanka](https://github.com/ozdogan15/srilanka) | Code for paper 4, and ready Maha and Yala rice maps of Sri Lanka for 2010–2024 in Google Earth Engine | None given: ask the author before reusing the code |
| [WorldCereal/worldcereal-classification](https://github.com/WorldCereal/worldcereal-classification) | Cropland and crop-type maps in the cloud (openEO, Presto model) | MIT |
| [dl4sits/BreizhCrops](https://github.com/dl4sits/BreizhCrops) | Time-series models (LSTM, TempCNN, Transformer) to use as baselines | GPL-3.0: shared code that includes it must also be GPL |

## Team work

Tasks and weekly updates live in the main repo, [jarvis-uom/IS4990-project](https://github.com/jarvis-uom/IS4990-project). The Paddy check is [issue #4](https://github.com/jarvis-uom/IS4990-project/issues/4).
