## For your information
Original EPG repository is in an archived state. See https://github.com/weareblahs/epg-old for the original one.
## Currently encountered problems
No Problems.
## Solved problems
- HITZ FM EPG Unavailable.
- BBC World News HD (String was not recognized as a valid DateTime)
  - Now using SiteIni by aa6my ([See here](https://github.com/weareblahs/epg/issues/2#issuecomment-841613022)), most of the channels that returned "String was not recognized as a valid DateTime" are fixed. All of the EPG data should be working now.
- Some channels unavailable on Astro.
  - Fixed: Changed the unavailable WebGrab ID from SD channel ID to HD channel ID.

## Updates
FOUND: unifi PlayTV is powered by Huawei's Envision Video Platform.
 - [Here is an example of the EPG data for this platform.](https://gist.github.com/weareblahs/89fc50e4011094628749b6362187e669)
 - If someone made a SiteIni for unifi TV (Unencrypted), please contact me through [my email](https://gist.github.com/weareblahs/dccd48e74be31ec770a09036d97c02a8) and I will process it as soon as possible to update the unifi TV Guide through unifi.com.my.
   - the SiteIni file will not be uploaded into GitHub.
## Auto-update bot information
The auto-update process will run daily.

# About

This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro and RTM for providing channel guide (and SingtelTV / Hong Kong Cable TV (Mainly for BBC Channels on unifi TV) for some of the channels).

# Currently available providers (Slowly Updating Right Now)
- Astro

- unifi TV (Partial Channels, **not including unifi Sports and unifi TV in-house channels** (like HyppSensasi and Dunia Sinema))
    
    - **Extra Stuffs Available!** [Watch unifi TV on your IPTV player, legally!](https://github.com/weareblahs/unifi-tv) (I made that repository, too)
    
- RTM Klik (RTM-operated Channels only, not including radio stations)

- MYTV Broadcasting (aka myFreeview) (Including RTM Radio Stations)

    # Providers Coming Soon

    - Sirius TV

# Current Channel Statistics
## Total Channels
- Astro: 192 (including Astro First, Astro Best and Radio Channels)
- unifi TV: 57 (Partial Channels Only)
- RTM Klik: 8
- MYTV Broadcasting: 21
## Channel Source
- Astro: astro.com.my
- unifi TV: astro.com.my / i-cable.com / singtel.com.sg / nowtv.now.com / peotv.com / sfr.fr (Luxe TV and France24) / sky.com
  - Inaccurate EPGs are Star Chinese Movies (Singapore Feed?), Now Jelli (Feed from Hong Kong, different from other areas), Sony SAB and Sony SET (Modified Feed by unifi TV to add local content), Colors Cineplex (UK Feed)
  - See Fix [Here](https://github.com/weareblahs/unifi-tv#epg-for-polimer-and-jaya-max) for Polimer and Jaya Max EPGs (Note that you must have a IPTV player capable of multiple EPG sources)
- RTM Klik: rtmklik.rtm.gov.my
- MYTV Broadcasting: rtmklik.rtm.gov.my / astro.com.my  
## XMLTV ID Type
- Astro: Channel Number
   - [Astro GO Exclusive Channels XMLID](https://weareblahs.github.io/epg/misc/AGEC.md)
- unifi TV: Channel Number  
- RTM Klik: [Channel List Here](https://weareblahs.github.io/epg/misc/RTMK.md)
- MYTV Broadcasting: Channel Number  
## Download Links / Links to copy into your IPTV player
- Astro: https://weareblahs.github.io/epg/astro.xml
  - Astro (Compressed): https://weareblahs.github.io/epg/compressed/astro.xml.gz
- unifi TV: https://weareblahs.github.io/epg/unifitv.xml  
  - unifi TV (Compressed): https://weareblahs.github.io/epg/compressed/unifitv.xml.gz
- RTM Klik: https://weareblahs.github.io/epg/rtmklik.xml  
  - RTM Klik (Compressed): https://weareblahs.github.io/epg/compressed/rtmklik.xml.gz
- MYTV Broadcasting: https://weareblahs.github.io/epg/mytv.xml    
  - MYTV Broadcasting (Compressed): https://weareblahs.github.io/epg/compressed/mytv.xml.gz
# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.
