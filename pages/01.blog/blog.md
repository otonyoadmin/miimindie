---
title: Blog
hide_git_sync_repo_link: false
sitemap:
    changefreq: monthly
body_classes: 'header-dark header-transparent'
hero_classes: 'text-light title-h1h2 overlay-dark-gradient  hero-large parallax'
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
modular_content:
    items: '@self.modular'
    order:
        by: folder
        dir: dsc
content:
    items:
        - '@self.children'
    limit: 6
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: false
feed:
    limit: 10
    description: 'Sample Blog Description'
pagination: true
child_type: item
media_order: 'logoCombinesa.png,mimindlogonewoBmedium.png,_91951892_moon.jpg.webp,2mimindlogonewoB.png,doubleRainbow.jpg,ounilogoed-1.png,newbannerlogo.png,banner2b.png,banner2q.png,miimindLETTERS.png,miimndbanerfront.png,miimndbanerfront1.png,miimndbanerfront2.png'
hero_image: miimndbanerfront2.png
---

