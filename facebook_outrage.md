# Facebook Outage: What Went Wrong and Why Did It Take So Long to Fix?

> This article is more than 4 years old

Billions of users were unable to access Facebook, Instagram and WhatsApp for hours while the social media giant scrambled to restore services.

**By Josh Taylor** | Tue 5 Oct 2021 16:53 AEDT

---

Facebook and its other platforms, including Instagram, WhatsApp and Messenger, went down globally for close to six hours on Monday and Tuesday, depending on your time zone. As services are being restored, questions are being asked about what caused the outage, and why it took so long to fix.

---

## Why Did Facebook Go Down?

Just before 5pm UTC, people began noticing they could not access Facebook, Instagram, WhatsApp or Messenger. It would be more than five hours before services would begin to be restored.

Facebook issued a statement on Tuesday confirming that the cause of the outage was a **configuration change to the backbone routers** that coordinate network traffic between the company's data centres, which had a cascading effect, bringing all Facebook services to a halt.

It meant not only was Facebook gone, but everything Facebook runs disappeared too.

Others have provided a bit more detail on why Facebook vanished from the internet. Cloudflare — which had its own recent internet outage issues — has provided a detailed explanation about what happened.

It involves two things that sort out how the internet is the internet: **Domain Name System (DNS)** and **Border Gateway Protocol (BGP)**.

The internet is a lot of connected networks. So that means to keep order of things, you need something like BGP to tell you where you need to go. DNS is essentially the address system for the location of each website — its IP address — while BGP is the roadmap that finds the most efficient way to get to that IP address.

> *"Facebook (accidentally, we assume) sent an update to a deep-level routing protocol on the internet that said, basically, 'hey we don't have any servers any more xoxo'"*
> — Alex Hern (@alexhern), October 4, 2021

Cloudflare said Facebook on Monday essentially told BGP through a series of updates that those paths to Facebook no longer existed — not just for Facebook, but everything Facebook runs. That meant people trying to reach Facebook couldn't find the path to access it.

---

## Why Were Instagram, Messenger and WhatsApp Down?

All of Facebook's services were affected, not just Facebook. It included Facebook's own internal systems, with reports staff were locked out of offices, and could not access their own internal communications platform.

---

## Why Did It Take So Long to Fix?

Facebook's own internal systems are run from the same place, so it was hard for employees to diagnose and resolve the problem.

As the Guardian's UK technology editor, Alex Hern, put it on Twitter: *"Facebook runs EVERYTHING through Facebook"*, so the usual way you would fix a problem like this was also not working.

Facebook staff were reportedly unable to access their own communications platform, Workplace, and were unable to access their office due to the security pass system being caught up in the outage.

Facebook indicated the duration and severity of the outage meant the systems were being brought back to full capacity slowly.

---

## How Did They Eventually Fix It?

Facebook so far has not gone into much detail about what went wrong and how it was fixed, but there were multiple reports the social media giant **sent a technical team out to its servers in California to manually reset the servers** where the problem originated.

---

## Can This Sort of Outage Be Avoided in Future?

This one is fairly uncommon but not something that can be completely avoided. However, the Facebook outage, along with others including the Cloudflare outage in 2020 and the Fastly one in June, show the problems with having a **single point of failure** for a vast number of online services people rely on.

People rely on Facebook not only to connect with friends and family, but businesses use it to log into other services including online sales websites. In some countries, it is the dominant means of communication through services like WhatsApp. That an outage can have such a profound impact on billions of people for several hours will give some pause for thought.

---

## Was My Personal Data at Risk?

No more than when Facebook is up and running.

---

## Isn't This All Weird Timing for Facebook?

Yes. Facebook is not having a good time right now. Last week Facebook paused a plan to launch Instagram for kids, after leaked internal research showed the company was aware the app could affect girls' mental health.

Then on Sunday, the former Facebook civic integrity product manager **Frances Haugen** went public with explosive allegations that Facebook had prioritised growth and profit over public safety.

> *"The version of Facebook that exists today is tearing our societies apart and causing ethnic violence around the world."*
> — Frances Haugen, speaking on 60 Minutes

---

## How Much Did It Cost?

We haven't seen a cost estimate yet for how much it cost businesses who rely on Facebook. The outage, along with the whistleblower story on Sunday, prompted Facebook's share price to **drop 4.9%** on Monday, causing founder and CEO Mark Zuckerberg's personal wealth to drop **$6 billion**, according to Bloomberg.
