<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-dark.svg">
    <img src="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-light.svg" alt="FLAIR" width="320">
  </picture>
</p>

<p align="center">Open-source Laravel packages, made in Oxford.</p>

<h2 align="center">
  <a href="https://www.php.net/" target="_blank"><img src="https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat&logo=php&logoColor=white" alt="PHP 8.2+"></a>&nbsp;
  <a href="https://laravel.com/docs/" target="_blank"><img src="https://img.shields.io/badge/Laravel-12%20%7C%2013-FF2D20?style=flat&logo=laravel&logoColor=white" alt="Laravel 12 or 13"></a>&nbsp;
  <a href="https://packagist.org/packages/flairuk/" target="_blank"><img src="https://img.shields.io/badge/Packagist-FLAIRUK-F28D1A?style=flat&logo=packagist&logoColor=white" alt="flairuk on Packagist"></a>&nbsp;
  <a href="https://github.com/orgs/FLAIRUK/repositories" target="_blank"><img src="https://img.shields.io/badge/License-MIT-3DA639?style=flat" alt="MIT licence"></a>&nbsp;
  <a href="https://github.com/FLAIRUK" target="_blank"><img src="https://img.shields.io/badge/Made%20in-Oxford-002147?style=flat" alt="Made in Oxford"></a>&nbsp;
  <br>&nbsp;
</h2>

**FLAIR** publishes reference data for travel and commerce apps, clients for travel and transport APIs, and clients for the tills and payment providers that shops run on. Every package targets Laravel 12 and 13, is tested on PHP 8.2 to 8.5, and is MIT licensed.

<p align="center">
  🌍&nbsp;<a href="#-world-data">World data</a> ·
  🧳&nbsp;<a href="#-travel-and-transport">Travel and transport</a> ·
  🧾&nbsp;<a href="#-point-of-sale-and-payments">Point of sale and payments</a> ·
  🔒&nbsp;<a href="#-security">Security</a>
</p>

<br><br>

## 🌍 World

Countries, cities, airports, airlines and aircraft, looked up in memory with no database needed. Each dataset comes with a validation rule, and you can seed it into a table when other tables need to reference it.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-world">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-world/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-world/main/art/logo-light.svg" alt="flairuk/laravel-world" width="260">
        </picture>
      </a>
      <br>
      All five datasets behind one facade, joined through the country: a country's cities, airports and airlines, and one search across everything.
      <br>
      <code>composer require flairuk/laravel-world</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-countries">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-countries/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-countries/main/art/logo-light.svg" alt="flairuk/laravel-countries" width="260">
        </picture>
      </a>
      <br>
      All 249 ISO 3166 countries, with currencies, calling codes, regions, EEA membership and flags.
      <br>
      <code>composer require flairuk/laravel-countries</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-cities">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-cities/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-cities/main/art/logo-light.svg" alt="flairuk/laravel-cities" width="260">
        </picture>
      </a>
      <br>
      More than 9,000 IATA city codes, such as <code>LON</code>, <code>NYC</code> and <code>PAR</code>.
      <br>
      <code>composer require flairuk/laravel-cities</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-airports">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-airports/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-airports/main/art/logo-light.svg" alt="flairuk/laravel-airports" width="260">
        </picture>
      </a>
      <br>
      Over 10,000 IATA airport codes, from <code>LHR</code> to <code>AAA</code>.
      <br>
      <code>composer require flairuk/laravel-airports</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-airlines">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-airlines/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-airlines/main/art/logo-light.svg" alt="flairuk/laravel-airlines" width="260">
        </picture>
      </a>
      <br>
      IATA airline designators such as <code>BA</code>, <code>EK</code> and <code>QF</code>, with each airline's country.
      <br>
      <code>composer require flairuk/laravel-airlines</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-aircrafts">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-aircrafts/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-aircrafts/main/art/logo-light.svg" alt="flairuk/laravel-aircrafts" width="260">
        </picture>
      </a>
      <br>
      IATA aircraft type codes such as <code>320</code>, <code>738</code> and <code>388</code>.
      <br>
      <code>composer require flairuk/laravel-aircrafts</code>
    </td>
  </tr>
</table>

<br><br>

## 🧳 Travel and Transport

Clients for booking stays, trains and rides, and for live flight data, each set up from `.env` and testable with `Http::fake()`.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-booking-com">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-booking-com/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-booking-com/main/art/logo-light.svg" alt="flairuk/laravel-booking-com" width="260">
        </picture>
      </a>
      <br>
      A client for the Booking.com Demand API: accommodation search, availability and content, orders from preview to cancellation, and car rentals, with lazy pagination.
      <br>
      <code>composer require flairuk/laravel-booking-com</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-all-aboard">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-all-aboard/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-all-aboard/main/art/logo-light.svg" alt="flairuk/laravel-all-aboard" width="260">
        </picture>
      </a>
      <br>
      A client for the All Aboard rail API: European train journeys, offers, bookings, orders, rail passes and refunds, with no GraphQL to write.
      <br>
      <code>composer require flairuk/laravel-all-aboard</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-aviationstack">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-aviationstack/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-aviationstack/main/art/logo-light.svg" alt="flairuk/laravel-aviationstack" width="260">
        </picture>
      </a>
      <br>
      The aviationstack API: real-time and historical flights, airport timetables, future schedules and routes, with typed errors and lazy paging.
      <br>
      <code>composer require flairuk/laravel-aviationstack</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-uber">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-uber/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-uber/main/art/logo-light.svg" alt="flairuk/laravel-uber" width="260">
        </picture>
      </a>
      <br>
      The Uber APIs behind one facade: rides, guest and health rides, Uber Direct deliveries, the Uber Eats Marketplace and Uber for Business, with OAuth, cached app tokens and verified webhooks.
      <br>
      <code>composer require flairuk/laravel-uber</code>
    </td>
  </tr>
</table>

<br><br>

## 🧾 Payments

Clients for the till and payment systems shops run on, each set up from `.env`, testable with `Http::fake()`, and with install and status commands to check the connection.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/good-till-system">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/good-till-system/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/good-till-system/main/art/logo-light.svg" alt="flairuk/good-till-system" width="260">
        </picture>
      </a>
      <br>
      A client for the Goodtill EPOS API: products, customers, sales, reports and web orders, with tokens refreshed for you.
      <br>
      <code>composer require flairuk/good-till-system</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-square">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-square/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-square/main/art/logo-light.svg" alt="flairuk/laravel-square" width="260">
        </picture>
      </a>
      <br>
      Square payments through the official SDK, with signature-checked webhooks as Laravel events, OAuth, idempotency keys and a card form.
      <br>
      <code>composer require flairuk/laravel-square</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-sumup">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-sumup/main/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-sumup/main/art/logo-light.svg" alt="flairuk/laravel-sumup" width="260">
        </picture>
      </a>
      <br>
      SumUp online checkouts, card readers, refunds and OAuth through the official SDK, with each webhook confirmed against the API.
      <br>
      <code>composer require flairuk/laravel-sumup</code>
    </td>
    <td width="50%"></td>
  </tr>
</table>

<br><br>

## 🔒 Security

Please report a vulnerability privately through the affected repository's **Security** tab ("Report a vulnerability") rather than in a public issue. Each repository's `SECURITY.md` has the details.

<br><br>

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/divider-dark.svg">
    <img src="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/divider-light.svg" alt="" width="100%" height="1">
  </picture>
</p>

<div align="right">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-dark.svg">
    <img src="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-light.svg" alt="FLAIR" width="96" align="left">
  </picture>
  <sub><a href="https://github.com/orgs/FLAIRUK/repositories" target="_blank">Repositories</a> · <a href="https://packagist.org/packages/flairuk/" target="_blank">Packagist</a> · <a href="https://github.com/FLAIRUK/.github/tree/main/brand" target="_blank">Brand</a></sub>
  <br>
  <sub>Open-source Laravel packages, made in Oxford</sub>
  <br clear="left">
  <div align="left"><sub>© 2026 FLAIR. Every package is MIT licensed.</sub></div>
</div>
