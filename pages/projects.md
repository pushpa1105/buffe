---
title: Projects - BuffeDon
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
projects:
  Current Focus:
    - name: 'Keela'
      link: 'https://www.keela.co/'
      desc: 'Fundraising & Donation Management Platform'
      icon: 'i-simple-icons-keras'
    - name: 'Goodwill'
      link: 'https://github.com/pushpa1105/goodwill-app'
      desc: 'Platform for trading and investment activities'
      icon: 'i-logos-nuxt-icon saturate-0'

  Websites / Company:
    - name: 'CloudTech Services'
      link: 'https://cloudtechservice.com/'
      desc: 'Software Development company'
      icon: 'i-simple-icons-cloudera'
    - name: 'B2pip'
      link: 'https://github.com/pushpa1105/demo-two/tree/master'
      desc: 'Platform for trading and investment activities'
      icon: 'i-carbon-type-pattern'

---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
