---

layout: col-sidebar
title: OWASP Harare
tags: example-tag
region: Africa

---
## Welcome
Welcome to the OWASP Harare Chapter Homepage. OWASP Harare is a local Zimbabwean Chapter with the sole objective of bringing together Application Security professionals and enthusiasts together to create a solid and mutually beneficial community. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert.

The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software.
<br/>


## Participation

OWASP Foundation is a professional association of [ global members](https://owasp.org/membership/) and is open to anyone and everyone interested in learning more about application security. Local chapters are run independently and guided by the[Chapter\_Leader\_Handbook](https://owasp.org/www-policy/operational/chapter-handbook-existing). As a [501(c)(3)](https://owasp.org/about/) non-profit professional association your support and sponsorship of any meeting venue and/or refreshments is tax-deductible. Financial contributions should only be made online using the authorized online chapter donation button. To be a <b>SPEAKER</b> at
any of the Chapter's evnts, simply review the [ speaker agreement](https://owasp.org/www-policy/legal/speaker-agreement) and then contact the local chapter leader(s) with details of what OWASP PROJECT, independent research or related software security topic you would like to present on.

<br/>

## Sponsorship/Membership

<a href="https://owasp.org/donate/" target="_blank"><img src="assets/images/Btn_donate_SM.gif" alt=""/></a> to this
chapter or become a local chapter supporter. Or consider the value of [Individual, Corporate, or Academic Supporter membership](https://owasp.org/membership/). Ready to become a member? <a href="https://owasp.org/membership/" target="_blank"><img src="assets/images/75px-Join_Now_BlueIcon.jpeg" alt=""/></a>
<br/>

## Chapter Volunteers

Volunteering carries many benefits including meeting great people, learning new skills, and above all – fun\! We appreciate the assistance
that our volunteers provide to ensure our events run smoothly. If you would like to help out for few hours with administrative tasks on the
day of events, please reach out via [email](mailto://donald.munengiwa@owasp.org) or twitter.
<br/>

## Next Meeting/Event(s)

Chapter meetings are held several times a year, typically at a location
provided by our current facility sponsor.

{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });

  
</script>

#### TICKETS:

This event will be free to attend for both members and non-members of
OWASP and is open to anyone interested in application security and cyber
security.

Register to attend this event at [meetup](https://www.meetup.com/OWASP-Harare-Chapter/events/). 

You can register to learn about our future events via the OWASP Harare page at
[meetup.com](https://www.meetup.com/OWASP-Harare-Chapter/)

**Code of Conduct**:

  -   
    We hope you enjoy our events, we care deeply about inclusivity and
    diversity so that OWASP is a comfortable and welcoming community for
    everyone. Please reach out to one of our chapter leaders if you have
    any feedback or would like to speak to us, we take these matters
    very seriously. You can find out more about our policies here:
    [https://owasp.org/www-policy/operational/events](https://owasp.org/www-policy/operational/events)

<br/>

## Speaking at OWASP Harare Chapter Events

#### Call For Speakers

Call For Speakers is open - if you would like to present a 15-45 minute
talk on Application / Cyber Security at future OWASP Harare Chapter
events - please review and agree with the [ OWASP Speaker
Agreement](https://owasp.org/www-policy/legal/speaker-agreement) and submit your
talk/presentation via [Google
Forms](https://forms.gle/A3GG9X9qEFrPDL85A)
<br/>
Please note that you can also pair up with a colleague and present a
joint talk. Please ensure that your talk is objective, stresses open
source approaches, and avoids references to any commercial offerings of
your company. We are looking forward to your submissions
