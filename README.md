# DIY Small HEPA Air Purifier
Herein lies the thought process behind and instructions for building a relatively quiet, low-foorprint HEPA-rated Air Purifier, with modding options.

Add image or render of build here

# Credits and Similar
To credit my inspiration, and in case this project isn't what you're looking for, here are some links:

* https://www.reddit.com/r/crboxes/comments/1351iqw/diy_batterypowered_hepa_air_purifier/
* https://www.youtube.com/watch?v=6Vmh2Ip2Vxg
* https://github.com/Kels316/DIY-Air-Purifier
* https://www.cleanairkits.com/products/exhalaron
* https://github.com/jcorbin/pchepa/
* https://www.reddit.com/r/functionalprint/comments/1f3ym1n/my_take_on_a_diy_air_purifier_still_a_work_in/
* https://github.com/jon-harper/air_filter?tab=readme-ov-file

And of course, if the CADR is too low for your purpose, here's a helpful guide for a much bigger unit, the Corsi-Rosenthal box / Comparetto Cube:
https://github.com/wrichter/GermanyDYIAirCleaner

# Design Process
## Requirements
The design has to be quiet, effective, with interchangeable parts, and exhibit some amount of fiduciary responsibility.

For effectiveness, we look at the CADR, or Clean air delivery rate, a measure of how much clean air is being emitted by the system.[^1]
[^1]: https://en.wikipedia.org/wiki/Clean_air_delivery_rate#Understanding_the_rating

For a given room volume (square footage * ceiling height), we can similarly use ACH, or Air Changes per Hour, to see how quickly the system can completely filter the air in a given room.[^2]
[^2]: https://en.wikipedia.org/wiki/Air_changes_per_hour

For quietness, we compare the noise performance of a different PC Fans, and exclusively looking at PC fans due to their optimized designs for size, efficiency, cost, and acoustic pressure (noise) profile. 

## Fan Selection
Arctic P12 Pro A-RGB:
https://www.arctic.de/us/P12-Pro-A-RGB/ACFAN00309A

HWCooling.net has charts comparing test scores between various fans, and that coupled with user anecdotes on reddit led me to pick the Arctic P12 Pro A-RGB for this build (static pressure charts seen here: https://www.hwcooling.net/en/arctic-p12-pro-a-rgb-the-benchmark-for-illuminated-fans-review/22/)
The 140 mm fans move more air at a greater pressure, but are also louder (add quantitative testimonials?), and so the 120mm Arctic fans were chosen.

Also RGB Lights are cool, maybe this can double as a lamp. HWCooling.net show it having a max white light luminance of 1684 lx (lx being the lux, the luminance flux per area, or lumens / square meter)[^3]. 

From, the IES Handbook via https://www.bannerengineering.com/us/en/company/expert-insights/lux-lumens-calculator.html, we have this chart, which leads me to believe that the RGB on the fan is bright enough to serve as a lamp for a kitchen or living room:
|     Application    | Recommended Lux Ages 25-65 | Recommended Lux Ages 65+ |
|:------------------:|:--------------------------:|:------------------------:|
|  Warehouse         |  100                       |  200                     |
|  Work area         |  150                       |  300                     |
|  General assembly  |  1,000                     |  2,000                   |
|  Detailed assembly |  2,000                     |  4,000                   |
|  Fine inspection   |  5,000                     |  10,000                  |

[^3]: https://www.hwcooling.net/en/arctic-p12-pro-a-rgb-the-benchmark-for-illuminated-fans-review/41/
## Filter Selection
Given the selection of 120 mm fan, we need the HEPA filter to have an opening of at least 120mm. A larger cylinder would actually improve performance, by increasing the surface area and leading to a less severe pressure drop across the filter.

## Power Supply





