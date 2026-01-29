---
title: Projects - Pushpa
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
projects:
  Current Focus:
    - name: 'Felt & Yarn'
      link: 'https://www.feltandyarn.com/'
      desc: 'Company that produces and sells handicrafts felt supplies.'
      icon: 'i-simple-icons-flat'
    - name: 'Tekkon'
      link: 'https://tekkon.com.np/'
      desc: 'Software company providing digital solutions.'
      icon: 'i-simple-icons-toml'
    - name: 'Naya'
      link: 'https://iznaya.netlify.app/'
      desc: 'Fan Project'
      icon: 'i-simple-icons-naver'

  Websites / Company:
    - name: 'Keela'
      link: 'https://www.keela.co/'
      desc: 'Fundraising & Donation Management Platform'
      icon: 'i-simple-icons-keras'
    - name: 'Goodwill'
      # link: 'https://github.com/pushpa1105/goodwill-app'
      desc: 'Platform for trading and investment activities'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'CloudTech Services'
      link: 'https://cloudtechservice.com/'
      desc: 'Software Development company'
      icon: 'i-simple-icons-cloudera'
    - name: 'B2pip'
      link: 'https://singular-florentine-77ef0c.netlify.app/'
      desc: 'Platform for trading and investment activities'
      icon: 'i-carbon-type-pattern'

---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
