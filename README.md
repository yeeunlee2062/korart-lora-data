# KORART LoRA training data

Training sets for the FLUX.1-dev LoRA used in "From Intent to Artifact" (revision). Each zip holds JPEG photographs of museum artifacts with one caption file per image (`<relic_id>.txt`).

- `train_all.zip`: 333 artifacts (all valid reference photographs). Used for the web page model.
- `train_fold0.zip` … `train_fold4.zip`: the same, without any artifact listed in that fold's 20 test combinations (262–268 images each).
- `training_sets.csv`: image, combination, pixel size and caption for every set.

Images: e-museum (National Museum of Korea, https://www.emuseum.go.kr), Korea Open Government License type 1 (attribution). Image `<relic_id>.jpg` corresponds to `https://www.emuseum.go.kr/detail?relicId=<relic_id>`. Images with a long side above 1024 px were reduced to 1024 px; nothing was cropped.
