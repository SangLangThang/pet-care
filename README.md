# PetCare

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


body
  header(share UI)
    section.header
    nav.top-nav

  main(share UI)
    section.hero
    section.services

  footer(share UI)
    section.subscribe
    section.footer



section.topbar
  .container
    .row
      .col
        ul.top-bar__contact-info > li* 2 > a  > i
      .col
        ul.top-bar__social-list > li* 4 > a  > i

section.top-nav
  .container
    .row
      .col
        img.top-nav__logo
      .col
        ul.top-nav__menu > li* 6 > a 
      .col
       .top-nav__vertical-line
      .col
        ul.top-nav__icons > li*2 > a > i
      .col
        .top-nav__contact-phone

section.hero (background-image)
  .container-fluid
    h1.hero__title
    h4.hero__subtitle

section.services
  .container
    .row
      .col * 8
        div.service__item
          img.service__item-thumbnail
          img.service__item-logo
          h3.service__item-title
          p.service__item-sub
          button

section.footer
  .container
    .row
      .col 
        div.footer__logo-wrapper
          img.footer__logo
        p.footer-text
        ul.footer__social-list > li * 4 > a > i
      .col
        .footer__item-header
        ul.footer__links-list > li * 5 > a 
      .col
        .footer__item-header
        div.footer_galerry
          .row
            .col * 6
              .footer__galerry-image
                img
      .col
        .footer__item-header
        div.footer_contact
          ul.footer__links-list > li * 5 > a  > i
    .row
      .col
          img.footer-subscribe__icon
          p..footer-subscribe_text
      .col
        input..footer-subscribe__input
        img.footer-subscribe__input-icon


