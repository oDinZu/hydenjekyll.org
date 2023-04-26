# Summary
This web application is the core website for SharpeTronics.com. It is a live JAMstack (Jekyll, API's, Markup) of a website with *micro services* that includes all the bells and whistles for comments, newsletter subscriptions, content management systems (CMS), site generators, blog posts, continuous deployment (CD) and integration (CI), git version management, Stripe ecommerce shopping, progressive web applications (PWA), and much more.

Our stack architecture reflects minimal need for Javascript, Php and Sql and preserves the speedy *reactivity* of the modern web architecture. 

Our architecture trumps in security, file size and modularity, while expediting sonic load times and reducing the learning curve for web developers and editors alike!

We focus on quality *design* and *content*; while creating increased portability, automated testing, speedy load times and secure lightweight web apps.

No proprietary operating system dependencies required, only Docker Engine super machines and some tender love and care (TLC).

## Architecture Features
* JAMstack (Jekyll, API's, Markup)
* Lightweight, Responsive & Static!
* SCSS ready!
* Developer Friendly!
* Editor Friendly!
* Docker super machines!
* Web3 Ready!
* Blog ready with *collections* and *pagination*.
* SharpeTronics Pages ready (free GitHub hosting or premium hosting).
* Continuous Integration (CI), Continuous Delivery (CD) & Automated platform.
* Backups galore for restoring to previous states.
* Headless CMS with Strapi superpowers!
* Ease of use for editors and writers.
* Distributed CDN with automatic HTTPS (Cloudflare).
* Secure Ecommerce shopping with Snipcart.
* International Multi-language
* Commenting System with moderation (*pending*)
* Secure SharpeTronics (ST) hosting that is flexible, lightning fast and inexpensive.

## Jekyll Plugins
* Menus
* Tagging
* Archives
* Pagination v2

## Strapi Plugins
* Slugify
* Media Library
* Import Export Entries *upload/download or migrate products and posts*

## Socials
* Discord: https://discord.gg/jB4mXBsZjd
* Facebook: [https://facebook.com/sharpeetronics](https://facebook.com/sharpeetronics)
* Twitter: [https://twitter.com/sharpetronics](https://twitter.com/sharpetronics)
* Email: info@sharpetronics.com
* Telegram: [https://t.me/+oFUwKSn3frgzZDFh](https://t.me/+oFUwKSn3frgzZDFh)

# Development

## API's
* SharpeTronics Strapi Content Management System (CMS)
* Stripe Ecommerce Integration

## System Requirements (Development)
* Install & Configure Docker Engine (Community)
* Install & Configure Docker-Compose
* Install & Configure Git

*All Ruby dependencies are created and stored in a Docker container.*
*Currently, the integration is maintained with Ubuntu 20.04 LTS Linux operating system, although, it is possible to use with Macintosh or Windows. The setup with docker and docker-compose will be similar as the Linux workflow; please see **Further Reading** for more details or get involved at: https://discord.gg/jB4mXBsZjd.*

### Clone, Build & Launch
1. ```git clone https://git.sharpetronics.com/sharpetronics/sharpetronics.com.git```
2. ```cd sharpetronics.com```
3. ```rename /_plugins to /BAK_plugins``` *to make use of these plugins, you need to be authorized*
3. ```docker compose up```
4. ```open a web browser and navigate to: localhost:4000```

**Happy Hacking!!!** :star:

## Further Reading
* Docker Engine https://docs.docker.com/install/
* Docker Compose https://docs.docker.com/compose/install/
* Jekyll https://jekyllrb.com/
* Git https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
* Strapi https://docs.strapi.io/developer-docs/latest/getting-started/introduction.html
* Snipcart https://snipcart.com/
* SharpeTronics Custom Ruby Plugin (LICENSE: GPLv3)
