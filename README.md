# MeWe Cleanup Filter

This filter list, originally created with Brave's built-in ad blocker ("Brave Shields"), is based on my own frustrations with recent UI changes to MeWe, a privacy social network. I got tired of supposedly opt-in ads being pushed in my face everywhere I went. I was initially on board with a lot of the changes added to the platform over the previous year but in the last two months (as of creating this repo), they've been implementing more and more changes that are downright bizarre and even anti-consumer. On many occasions, I attempted to voice feedback but was repeatedly shot down with my suggestions and feedback. As such, I decided to take matters into my own hands as far as I legally and ethically could, by creating this blocklist. For me, it was just a matter of personal preference, but I'm certain others can benefit from it.

## What it does

It completely blocks the following:
- All of the "optional" ad boxes from all feeds
- The Soshi wallet button
- The "locked content" option on the updated posts menu
- The "mint your group" box for group owners (since this list blocks the ads/wallet anyway)
- The junk links on the bottom left (mostly just links to ToS/privacy policy and such)
- The stories bar
- The Explore feed
- The obnoxious MeWe Premium banner at the top of the [store page](https://mewe.com/store)

### Why does it block x/y/z?

The reason I set this up the way I did was because the ads weren't the only thing bugging me. I also got tired of the asymmetry in the UI side panels, and I absolutely abhor the recent push for pressuring users to see and follow public accounts' content which is why I blocked the stories bar and Explore feed as wel. MeWe is supposed to be a **PRIVACY** social network, not a public-first social network like a microblogging platform.

## What it doesn't do

It doesn't remove Soshi entirely, obviously. It also doesn't bypass the ridiculous paywalls that people can hide their posts behind, as I can't legally help people evade paywalls. Further, I didn't block the new "My Apps" menu on the left side panel because those aren't inherently anti-consumer. 

Additionally, for legal reasons, I would like to state categorically that **this doesn't do anything illegal**. This is simply a customized version of your standard ad blocker [many people run](https://odysee.com/@rossmanngroup:a/why-i-support-adblockers-why-you-should:c) in their browsers today. 

Literally **any user could manually do everything I've done here** by using the "Block element" feature through their ad blocker. This is just a means of making it simpler based on my own experimentations with the "Block element" feature.

## How to use

There are two ways you can add this. The simplest way is to add the URL of the `mewecleanup.txt` file to your ad blocker's filter lists. Alternatively, you can add a non-updating version by directly copying the data from the file and pasting it as a custom filter rule.

### Brave Shields

Click on the Brave Shields icon in the address bar and selecting the **Filter lists** button at the bottom of that menu. Navigate to **Add custom filter lists** and paste the [URL to the file](https://raw.githubusercontent.com/tenshi-net/mewe-cleanup-filter/refs/heads/main/mewecleanup.txt) in the text box.

_For the non-updating version:_ copy the data from `mewecleanup.txt`. Navigate to the **Create custom filters** section and enable Developer mode. From there, copy the contents of `mewecleanup.txt` and paste them at the bottom of the **Create custom filters** menu and save your changes.

### uBlock Origin

Open your uBlock settings menu. Navigate to the **Filter lists** tab. Scroll to the bottom, to the section labeled "Import...". Paste [the URL](https://raw.githubusercontent.com/tenshi-net/mewe-cleanup-filter/refs/heads/main/mewecleanup.txt) into that text box and select **Apply changes**.

_For the non-updating version:_ copy the data from `mewecleanup.txt`. Navigate to the **My filters** tab. Paste the contents of `mewecleanup.txt` to the bottom of the text section. Ensure "Enable my custom filters" is ticked and then **Apply changes**.

## Disclaimer

I don't hate MeWe. Not by a long shot. I love it and I understand it needs to be profitable in order to survive and grow. I'm also not opposed to opt-in ads entirely, but I do refuse to support ads if they're continually made **more** intrusive, **less** optional, and the basis upon which the company continues to take away features and value from customers. If you enjoy MeWe as I do and you use this list, I highly encourage you to consider subscribing to MeWe Premium. It's a great value if you use the platform regularly and I would bet it provides a lot more financial support than these ridiculous ads have. 

It's important to support them if you like the platform because they don't monetize our data. I just don't agree with the way they're attempting to bring in extra income through alternative means.
