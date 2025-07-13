## Contents
- [India-Visa-Online](#india-visa-online)
  - [The website](#the-website)
  - [Preparation](#preparation)
    - [Browser](#browser)
    - [Mail/DNS](#maildns)
    - [Passport photo](#passport-photo)
    - [Scan of the passport](#scan-of-the-passport)
  - [The forms](#the-forms)
  - [Technical Contact in India](#technical-contact-in-india)

# India-Visa-Online <a id="india-visa-online"></a>

Applying for a visa for India can be very cumbersome and time-consuming. Here is a short summary of the problems I have encountered and their solutions.

Only the e-tourist visa is described here.

## The website <a id="the-website"></a>

The official website is <https://indianvisaonline.gov.in>.  
As you will see, it looks quite outdated and if you dare to take a look at the HTML or Javascript code, don't be shocked, but be happy that the page is still running.

## Preparation <a id="preparation"></a>

### Browser <a id="browser"></a>

The website recommends Firefox, Chrome or Internet Explorer 9 and above. I had the best experience with a recent Firefox. It can save you from hours of useless typing if you install a browser plugin which remembers your form input. For Firefox I used _Form History Control_ from <https://addons.mozilla.org/de/firefox/addon/form-history-control/>.

### Mail/DNS <a id="maildns"></a>

In the case you use your own DNS resolver and mail server, make sure your resolver has no problems with DNSSEC validation fails or add `nic.in` to the mailserver's whitelist for non-existent domains.

### Passport photo <a id="passport-photo"></a>

You need a scan of a passport photo with light background (not just a screenshot from the passport). The European standard portrait format 35 mm × 45 mm is too tall, it must be possible to crop it so that it is almost square. Only JPEG files are accepted.  
It appears that you need “an unsigned recent color photograph” to attach to the printed confirmation form.

### Scan of the passport <a id="scan-of-the-passport"></a>

You have to upload a scan of the passport page(s) with the relevant personal information. Yes, the same information you've already entered in the application. The scan has to be readable and must not exceed 300 kB. Only PDF files are accepted.

## The forms <a id="the-forms"></a>

At some times or days it is apparently not uncommon to lose the contact to the server. To avoid having to start again from the beginning, enter the **temporary application ID** (which is displayed after the submission of the first application form page) in the "partially filled data" entry at the start page. Additionally you can re-enter your data with the help of _Form History Control_.

Many things are requested, but the Javascript check during input is usually strict enough that it is almost impossible to enter incorrect data. An important exception are the **telephon numbers:**

Note that country codes preceeded by a ***+*** are accepted as input, but lead to a endless loop with empty forms or to HTTP 500 or to strange messages, that a server name does not exist. So never use, e.g., ***+91 555 …***, but ***0091 555 …***.

## Technical Contact in India <a id="technical-contact-in-india"></a>

As technical contact I've found hidden in a webpage the [e-TV Support Team](mailto:indian-evisa@gov.in).  
In response to described technical problems that clearly exist on the server side, you are advised to use an up-to-date Internet Explorer and to delete cookies. 🤪

---

<sub>Fri Jun  6 05:32:32 UTC 2025</sub><sup>_0.0.4_</sup>
