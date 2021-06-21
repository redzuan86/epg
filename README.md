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

## Auto-update bot information
The auto-update process will run daily.

## Important information
Do not fork it unless you want to change something on the configuration files, as it will not update the EPG by itself! If you want to update it, modify "GenerateAll.bat" to point to your WebGrab directory and repository directory. Make sure you have git setted up on the epg directory (you might have to use ``del .git`` to delete the existing one, then link it to your own fork). If you want to update it locally, delete all lines that contain the "git" command.

# About
This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro and RTM for providing channel guide (and SingtelTV / Hong Kong Cable TV (Mainly for BBC Channels on unifi TV) for some of the channels).
# Credits
Thanks to Khalis (@hantu08 on Telegram) for helping me doing some WebGrab+Plus stuffs, including:
 - Access to unifi TV Channel Guide directly from playtv@unifi  
 - Access to the new Astro Guide page (content.astro.com.my)
 - Access to the new RTM Klik SiteIni

# Currently available providers (Slowly Updating Right Now)
- Astro

- unifi TV

- RTM Klik

- MYTV Broadcasting (aka myFreeview) (Including RTM Radio Stations)

    # Providers Coming Soon

    - Sirius TV

# Current Channel Statistics
## Total Channels
- Astro: 192 (including Astro First, Astro Best and Radio Channels)
- unifi TV: 71
- RTM Klik: 8
- MYTV Broadcasting: 21
## Channel Source
- Astro: content.astro.com.my
- unifi TV: playtv.unifi.com.my
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