# Xhs AIO Actor Scraper
>This project enables you to extract posts and basic metadata from Xiaohongshu (also known as “XHS”) — perfect for gathering public-post data without manual browsing. It streamlines collecting content like images, descriptions and engagement metrics from a user’s feed or XHS homepage. The AIO actor provides a simple, programmatic approach to social-media data extraction.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Xhs AIO Actor Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
Xhs AIO Actor Scraper pulls publicly available data from XHS: posts, images, titles and engagement info. It solves the problem of manually copying data from a dynamic site that might use complex rendering or anti-scraping protections. It’s aimed at developers, data analysts, marketers or researchers needing structured social-media data from XHS.

### What the Scraper Covers
- Supports scraping the XHS homepage or specific user feeds to collect post data. :contentReference[oaicite:1]{index=1}  
- Fetches metadata such as post images, titles, descriptions, like counts and other visible data. :contentReference[oaicite:2]{index=2}  
- Can be triggered via API (JavaScript, Python, HTTP, CLI, or MCP) for automation and integration. :contentReference[oaicite:3]{index=3}

---

## Features
| Feature | Description |
|---------|-------------|
| Homepage & user-feed scraping | Collects posts from general feed or specific user profile on XHS. |
| Post metadata extraction | Captures title, description, cover image, all images in post, and like count (or other engagement metrics if available). |
| API-friendly | Fully usable via HTTP, JavaScript, or Python — integrates smoothly into existing workflows. |
| Batch or ad-hoc scraping | Runs for a single request or automated repeated runs depending on input config. |
| Export support | Output data stored in Apify dataset — easy to export as JSON or other formats via API. |

---

## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| cover | URL to the main cover image of the post or feed card. |
| title | Title of the post or feed entry (if available). |
| description | Post description or summary content (if available). |
| images | Array of URLs for images included in the post. |
| like_count | Number of likes or engagement metric of the post. |

---

## Example Output

    [
      {
        "cover": "https://img.xhs.com/123.jpg",
        "title": "小红书",
        "description": "小红书",
        "images": ["https://img.xhs.com/123.jpg"],
        "like_count": 100
      }
    ]

---

## Directory Structure Tree

    xhs-aio-actor/  
    ├── src/  
    │   ├── main.js  
    │   ├── crawler/  
    │   │   ├── xhs_fetcher.js  
    │   │   └── utils.js  
    │   ├── outputs/  
    │   │   └── exporter.js  
    │   └── config/  
    │       └── input_schema.json  
    ├── package.json  
    └── README.md

---

## Use Cases
- **Marketers or social-media analysts** use it to gather public post data from XHS for trend analysis or competitor monitoring.  
- **Researchers** collect image/post datasets to study social behavior or content patterns on Chinese social media platforms.  
- **Content aggregators** build catalogs of public posts (images, descriptions, metadata) for inspiration, curation, or archiving.  
- **Automation pipelines** periodically collect new posts for later processing — ideal for long-term monitoring or alerting systems.  

---

## FAQs

**Is the scraper still maintained?**  
No — the original actor is marked “Deprecated.” Users should consider this status before relying on it for production. :contentReference[oaicite:4]{index=4}

**Do I need an account or credentials to use it?**  
No — it scrapes publicly accessible content only. You just need an API token if you call via API. :contentReference[oaicite:5]{index=5}

**Can I scrape private posts or require login?**  
No — it works only on publicly available content (homepage or public user feed).  

**What happens if XHS changes site structure?**  
Since this actor is deprecated, structural changes on XHS may break scraping. Maintenance or custom adjustments might be required.  

---

### Performance Benchmarks and Results

**Primary Metric:** Successfully retrieves up to several dozens of posts per run depending on feed size and site response speed.  
**Reliability Metric:** Works reliably for publicly accessible feeds — failure mainly occurs when site structure changes or access is blocked.  
**Efficiency Metric:** Light on resources since it mainly fetches JSON or HTML and parses metadata; suitable for running periodically or in batches.  
**Quality Metric:** Provides full metadata (images, titles, likes) for the majority of posts when site elements remain unchanged.  



---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
