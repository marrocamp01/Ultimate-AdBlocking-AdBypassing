# Ultimate-AdBlocking-AdBypassing
Ultimate AdBlocking+AdBypassing Guide.md
# [AIO] Ultimate AdBlocking+AdBypassing Guide (Firefox/Chrome/Brave - Windows/Linux)

## Why We Need To Block Ads From Internet?

The Internet is a vast space of infinite knowledge. We can store and access those knowledge,
those data from everywhere and from any device.
We just need to use correct words or phrases to find them.
But often what we get is not exactly Safe to See, it's not annoyance-free.

That's why we need to filter out the annoyance and bad things. That's why we use Ad-Blockers.

Although some sites resist the users to use Ad-Blockers because the Site Owners gain revenue from the Ads to Pay their Domain+Hosting Bills.

## How Do We Get An Annoyance-Free Better Open Internet For All?

### [Highly Recommended] If you are looking for the _too easy_ way --

<a href="https://brave.com/rul801">
<img alt="Brave Browser" src="https://brave.com/static-assets/images/brave-bat-logos.svg" height="25vh" />
</a>

^ Install [Brave Browser](https://brave.com/rul801). Because as they say, _"You deserve a better Internet."_
> This browser is built upon Google Chrome, but with tons of customization done to make it faster and private. It natively blocks Ads, and you can also earn Brave Attention Token (BAT) as Reward. Don't forget to Read More while you Download & Install it for your PC using the unique link above.
> You can install the scripts and filters over Brave Browser for _True Ultimate AdBlocking+AdBypassing_.

#### There are two common ways to shut off the annoyance.

1. Block the known Domains or their IP Addresses through `hosts` file inclusion.
  > In Windows, `C:\Windows\System32\drivers\etc\hosts` or In Linux, `/etc/hosts`
2. Use AdBlock Browser Extensions and Userscripts to Block Specific Sites and their Scripts to be loaded inside any Website.
  > This is the Recommended Method

To do so, you need to follow the bellow steps as exactly as I written.
Do not tell me if you can't find a button to press or so.

## A Few Not-So-Simple Steps To Get Started With --

### [Recommended] Method #2, By the use of Browser Extensions and AdBlock Filters.

#### A. You need to Install four browser extensions.

  1. For Firefox, install [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/), [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) and [Universal Bypass](https://addons.mozilla.org/en-US/firefox/addon/universal-bypass/).
  2. For Chrome-based Browsers, install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo), [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) and [Universal Bypass](https://chrome.google.com/webstore/detail/universal-bypass/aihomhdbhpnpmcnnbckjjcebjoikpihj).

  > Please Remove / Uninstall any _Nano Defender_ addon or _NanoAdblocker_ filters from you Browser if you had installed any.
    There had been some issue going on with the lead developer stepping out for being too busy to maintain the Nano Projects.
    [Details about NanoAdblocker/NanoCore](https://github.com/NanoAdblocker/NanoCore/issues/362) are referenced here if anyone wanna dig in.

#### B. After you install the extensions, you have to install three Userscripts. Usable in either browser.

  1. [Anti-Adblock Killer (Script)](https://raw.github.com/reek/anti-adblock-killer/master/anti-adblock-killer.user.js) - A script to outthrow the Anti-Adblock parts from the websites,
  2. [AAK-Cont (Script)](https://gitlab.com/xuhaiyang1234/AAK-Cont/raw/master/FINAL_BUILD/aak-cont-script-ubo.user.js) - An updated form of previous Anti-Adblock Killer Script,
  3. [AdsBypasser](https://adsbypasser.github.io/releases/adsbypasser.full.es7.user.js) - To skip countdown ads & prevent ad pop-up.

#### C. Now, the (really) hard part. You have to add some filters to `uBlock Origin` which can eleminate specific Ad Domains and Scripts.

  1. Click on the _'uBlock Origin'_ Icon from the toolbar of your browser's toolbar. Then click the _Settings Icon_ which says 'Open the dashboard' when mouse is hovered.
  2. Go on the _"Filter lists"_ Tab. Scroll down & Tick the `[ ] import...` checkbox and add these lines bellow:
      ```
      https://raw.github.com/reek/anti-adblock-killer/master/anti-adblock-killer-filters.txt
      https://gitlab.com/xuhaiyang1234/AAK-Cont/raw/master/FINAL_BUILD/aak-cont-list-ubo.txt
      https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
      ```
      Click _Apply changes_.
  3. If you want to block Pornographic Sites in Browsers, Go to Step #C(2) and add the below line (40K entries) in the `[ ] import...` section:
      `https://block.energized.pro/extensions/porn-lite/formats/filter`
  4. If you want to block more Annoyance Sites, using an updated tracker, Go to Step #C(2) again and add the below line in the `[ ] import...` section:
      - If your Desktop/PC is old and running on very low CPU/RAM power, add the bellow line (46K entries) -
        `https://block.energized.pro/spark/formats/filter`
      - If your PC is new and have enough CPU/RAM power to simultaniously multitask smoothly, add the below line (203,865 entries) -
        `https://block.energized.pro/blu/formats/filter`
   
