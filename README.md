# 30DaysUAD

Live site: https://demoonism.github.io/30DaysUAD/

Hi Fellows, I am starting this repo as part of my effort to analyze the performance of our priporitory UAD on ViMo Platform.
For those of you who haven't heard of ViMo, it is a full fledge model training platform exclusivly designed for indsutry clients. In addition to our prioritory algorithms, we offer cool features such as AI-asssited label, Defect generation, Agentic user interface etc. 

UAD has always been an important algorithm on our platform, and it's nature sounds very suitable for manufacturing settings: lots of OK images, very limited NG images. however, it's application has not been as wide as the other supervised algorithms given the natures of manufacturing industry: large images (usually > 4096 x4096), rigid requirements (typically < 0.1% Miss Rate and < 0.5% Overkill).

A lot of efforts has been made to improve UAD algorithms in the recent years, and I want to systmatically evalute the sota on popular public datasets, as well as on our private, industry real dataset. 