# Min-Gyu's repo for WSI research
## Basic idea
 - Assumption 1: When patches get small enough but not too small, the patterns get very limited. It will resemble a compact codebook under vector quantization.
 - Assumption 2: Most patches carry little information. You probably don't need the entire KV table to get a representation for the whole slide.
 
## What should the repo look like?
### Compression
module for compression, which employs the key idea that can be both used for compressing whole slide images efficiently and to extract robust representation of them. Should including submodules for benchmarking / extracting private data, converting them, etc.

### Representation
module for extracting representation / feature, same as compression module / submodule for bench, data curation, etc.

### Generation
module for generating text based on the given representation of a WSI. This should include a training script for incorporating this module for existing open weight language models and proprietary models. Preferably data curation script should also be included or should define a schema for training data.
