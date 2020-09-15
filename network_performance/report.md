# Introduction

- Introduction on the purpose and scope of this report.
- Why BITAG is writing it
- Target audience
- Structure of document

# Recap of Pandemic Shutdowns in 2020 and the Impacts to the Internet
- Discuss here a short recap of the COVID-19 pandemic in 2020, government ordered shutdowns when they occurred and for how long, how this impacted society with a sudden shift to WFH, distance learning, social distancing, etc.
- High level observed changes in how the internet was used - more bandwidth, more usage, potential shifts in peak hour, changes in popular applications
- List and cite some of the key reported metrics, observations (e.g. 1 year's worth of bw growth in one month, peak hour shifting from 8pm to 2pm in some markets, etc.)
  - Nokia Deepfield Networks
  - Sandvine
  - Trade Associations (NCTA, CTIA, USTelecom, ACA, etc.)

# Closer Look at How the End-to-End Internet Ecosystem Responded
Short description of the E2E internet ecosystem and the key actors in this report

Content/Platforms <-+-> Transit/CDNS/Infrastructure <-+-> ISPs <--> Home networks <--> Applications

(Note add here a real diagram)

## Content/Platforms
[Netflix, NBCU, etc.]

[ 
- Describe here how the content/platforms responded and why
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access

]

## Transit Providers
[ATT. Lumens Technologies (aka CenturyLink), Others]

[ 

- Describe here how the transit providers responded and why
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access
  
]

## Content Delivery Networks
[Netflix, Akamai, Amazon]

[ 
- Describe here any observed changes in CDNS
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
  - Hit rate on caches before the shutdown and during shutdown
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access

]

## Infrastructure

[

[DNS providers, speed test providers]

Discuss here the observed and reported changes by the network infrastructure

- Capture here some of the reports from RIPE - Measured RTT, DNS latency
- Speed Test Measurement Platforms - Discuss changes is measured download and upload speeds

]

## Internet Service Providers
### Wired (Comcast, Charter, Century)

[ 

- Describe here how the ISPS responded and why
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
  - cellular offload to wifi
-  Call hold times, hand-off rates (mobile)
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access
  - providing connectivity (e.g. Keep America Connected Pledge)

]

### Wireless (Vistabeam)

[ 

- Describe here how the ISPS responded and why
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
  - cellular offload to wifi
-  Call hold times, hand-off rates (mobile)
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access
  - providing connectivity (e.g. Keep America Connected Pledge)

]

### Mobile (ATT, Comcast, Charter)

[ 

- Describe here how the ISPS responded and why
- How traffic was changing 
  - peak hour, 
  - peak traffic, 
  - traffic growth
  - geographic changes, 
  - concurrency/household, 
  - cellular offload to wifi
-  Call hold times, hand-off rates (mobile)
- Describe actions taken
  - scaling up, 
  - shifting resources, 
  - adding/changing routes, 
  - adding/changing CDNs, 
  - changing streaming rates
  - limiting or providing access
  - providing connectivity (e.g. Keep America Connected Pledge)

]

## Home Networks

[ If possible describe here observations and reports on home network peformance]

## Applications

- Mozilla Firefox
- Zoom
- Cisco Webex
- Netflix
- VPNs
- Social Networking (FB, WhatsApp, TikTok, etc.)
- Dropbox

[ 

Describe here how the application providers responded
- Temporarily disabling features such as HD or UHD video?
- Adding more security
- Re-routing through different data centers
- Opening up to make it easier for new users to sign on and use

]

# Observations

[ Discuss here BITAG observations gleaned from the data]

- Traffic went up in access networks, but did not measurably change on the transit networks indicating that the CDN and peering networks were working as designed
- Impact videoconferencing on the network
 - how much bandwidth videoconferencing really use on the upstream,
 - Traffic ratios (DS:US)- pre-shutdown they were ~20:1 and during the shutdown went down to ~16:1
- Cooperation across the ecosystem by actors

# Recommendations

[ Any possible BITAG recommendations ]

# References
- ACA https://acaconnects.org/covid-19/broadband-dashboard/ 
- CTIA - https://www.ctia.org/homepage/covid-19
- NCTA - https://www.ncta.com/COVIDdashboard
- US Telecom - https://www.ustelecom.org/research/network-performance-data/ 
- CWTA (Canada) - https://www.cwta.ca/wp-content/uploads/2020/05/English-Managing-Networks-in-Unprecedented-Times-May-25.pdf 
- Verizon - https://www.networkworld.com/article/3534037/update-4-28-how-enterprise-networking-is-changing-with-a-work-at-home-workforce.html 
- ATT - https://about.att.com/pages/COVID-19/network_archives.html 
- Comcast - https://corporate.comcast.com/covid-19/network 
- RIPE Atlas Data - https://atlas.ripe.net/landing/measurements-and-tools/ 
- NetForecast - https://www.netforecast.com/netforecasts-report-on-comcasts-network-performance-measurement-system-results-data/ 
- OECD - https://www.oecd.org/coronavirus/policy-responses/keeping-the-internet-up-and-running-in-times-of-crisis-4017c4c9/
- Nokia Deepfield Networks - https://storage.googleapis.com/site-media-prod/meetings/NANOG79/2208/20200601_Labovitz_Effects_Of_Covid-19_v1.pdf
- SamKnows - https://samknows.com/blog/samknows-critical-services-report-fixed-speed-usa
- OpenVault - https://openvault.com/covdi-19-broadband-usage-reaching-a-plateau-says-openvault
- Verizon - https://www.verizon.com/about/news/how-americans-are-spending-their-time-temporary-new-normal
- Neflix, Equinix, Dropbox & Zoom 
  - https://www.kentik.com/resources/how-leading-companies-support-remote-work-and-digital-experience/
  - https://www.zdnet.com/article/how-netflix-is-adjusting-network-operations-during-the-covid-19-outbreak/
- Akamai, Uber, Verizon Media - https://www.kentik.com/resources/how-leading-companies-support-remote-work-and-digital-experience-2-webinar/



# Glossary
