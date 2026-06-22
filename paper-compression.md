# Introduction
 - Tissue sildes are being digitalized faster with time
 - While traditional slide reviews and report communication can be digitalized, it causes staggering amount of disk usage (provide detailed analysis of cost due to secure storage)
 - Traditional lossy compression methods are inappropriate for this use case 
 - We either have to have a very good lossy compression or come up with a lossless compression with great compression ratio

## Related works
 - list general compression techniques first and describe why they are inappropriate for WSI (patchy artifact, etc)
 - focus on how research regarding compressing WSIs are on the increase, especially recently
 - list both neural network-based techniques and traditional techniques

## Problem formulation
 - WSIs contain a lot of repetition and have limited patterns (Some mathematical description maybe)
 - A compression "codec" optimized for WSIs should exploit this
 - Try to point out why recent works not really aligns with this (They rather focus on how humans evaluate the images more)
 - A good "modern" solution should be a good compression algo and not mess with current assist tools like AI

## In this study
 - we try to exploit successive cuts in a WSI
 - we use video codecs to do this
 - (might be nice if we can include the very-dense autoencoder stuff)

# methods
Fig. 1 should be a graphical abstract showing how our method works

## Compression ratio
 - Comparison between our method and other compression methods, including WSI-specific ones
 - Split different organs and other categories for supplementary materials
 - Include decompressed images too 

## Compute cost
 - Diagram shows how much compute is used for compression and decompression
 - CPU-only and GPU time is best

## Storage cost
 - Storage cost according to tissue types
 - best case scenario is lots of successive cuts 
 - worst is single cut slides only 

## AI-model sanity
 - Check if compression messes with currently available WSI models
 - Don't really know what's going to happen

# Conclusion
 - Methods focused on the characteristics of WSIs should be developed
 - WSIs will get digitalized more, so get ready
 - Research into compression will assist in enhancing AI usage in WSI by helping researchers understand WSI more 


