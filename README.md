# -goit-markup-hw-02

## Структура html

### Структура страницы

    body.page (.studio , .portfolio)

        header.page-header

        main

        footer.page-footer

### Структура Шапки

    header.page-header

        nav.navigation
            a.logo > span.accent-text
            ul.site-nav > li > a.site-nav-link.accent-hover

        ul.contacts > li > a.contacts-link.accent-hover

### Cтруктура Подвала

    footer.page-footer

        a.logo > span.accent-text
        address.address + ( span.white-text + span + span )

        b.subject.white-text
        ul > li*4 > a{ Instagram , Twitter , Facebook , LinkedIn }

        b.subject.white-text

        p.copyright

### Структура Studio (index.html)

    main
        section.studio-hero
            h1.studio-hero-title
            a.btn-accent

        section.studio-features
            ul > li
                a
                h3.studio-features-title
                p.studio-features-text

        section.studio-team
            h2.studio-section-title
            ul > li[lang=en]
                img
                h3.studio-team-title
                p.studio-team-role
                ul.studio-team-social > li > a

        section.studio-customers
            h2.studio-section-title
            ul > li*6 > a{ Логотип # }

### Структура Portfolio (portfolio.html)

    main > section

        .portfolio-filter > button[type="button"].btn-simple

        ul.portfolio-list > li > a.portfolio-item
            img
            h2.portfolio-item-title
            p.portfolio-item-text
            p.portfolio-item-tag
