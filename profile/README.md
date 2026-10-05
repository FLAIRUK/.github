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
  <a href="https://packagist.org/packages/flairuk/" target="_blank"><img src="https://img.shields.io/badge/Packagist-flairuk-F28D1A?style=flat&logo=packagist&logoColor=white" alt="flairuk on Packagist"></a>&nbsp;
  <a href="https://github.com/orgs/FLAIRUK/repositories" target="_blank"><img src="https://img.shields.io/badge/License-MIT-3DA639?style=flat" alt="MIT licence"></a>&nbsp;
  <a href="https://github.com/FLAIRUK" target="_blank"><img src="https://img.shields.io/badge/Made%20in-Oxford-002147?style=flat" alt="Made in Oxford"></a>&nbsp;
  <br>&nbsp;
</h2>

**FLAIR** publishes reference data for travel and commerce apps, and API clients for the tills that shops run on. Every package targets Laravel 12 and 13, is tested on PHP 8.2 to 8.5, and is MIT licensed.

<p align="center">
  🌍&nbsp;<a href="#-world-data">World data</a> ·
  🧾&nbsp;<a href="#-point-of-sale">Point of sale</a> ·
  🚀&nbsp;<a href="#-quick-start">Quick start</a> ·
  🔒&nbsp;<a href="#-security">Security</a>
</p>

<br><br>

## 🌍 World data

Countries, cities, airports, airlines and aircraft, looked up in memory with no database needed. Each dataset comes with a validation rule, and you can seed it into a table when other tables need to reference it.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-world">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-world/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-world/master/art/logo-light.svg" alt="flairuk/laravel-world" width="260">
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
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-countries/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-countries/master/art/logo-light.svg" alt="flairuk/laravel-countries" width="260">
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
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-cities/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-cities/master/art/logo-light.svg" alt="flairuk/laravel-cities" width="260">
        </picture>
      </a>
      <br>
      More than 9,000 IATA city codes. <code>LON</code> covers Heathrow, Gatwick, Stansted and the rest.
      <br>
      <code>composer require flairuk/laravel-cities</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/laravel-airports">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-airports/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-airports/master/art/logo-light.svg" alt="flairuk/laravel-airports" width="260">
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
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-airlines/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-airlines/master/art/logo-light.svg" alt="flairuk/laravel-airlines" width="260">
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
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/laravel-aircrafts/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/laravel-aircrafts/master/art/logo-light.svg" alt="flairuk/laravel-aircrafts" width="260">
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

## 🧾 Point of sale

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FLAIRUK/good-till-system">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/good-till-system/master/art/logo-dark.svg">
          <img src="https://raw.githubusercontent.com/FLAIRUK/good-till-system/master/art/logo-light.svg" alt="flairuk/good-till-system" width="260">
        </picture>
      </a>
      <br>
      A client for the Goodtill EPOS API: products, customers, sales, reports and web orders, with tokens refreshed for you.
      <br>
      <code>composer require flairuk/good-till-system</code>
    </td>
    <td width="50%"></td>
  </tr>
</table>

<br><br>

## 🚀 Quick start

```bash
composer require flairuk/laravel-world
```

```php
use FLAIRUK\World\Facades\World;

World::country('GBR')->name;                 // "United Kingdom"
World::airportsIn('GB')->pluck('code');       // LHR, LGW, MAN, …
World::countryOf(World::airlines()->find('BA'))->name;   // "United Kingdom"
World::code('BA');                           // Bosnia and Herzegovina, and British Airways
```

Each package's README covers the rest.

<br><br>

## 🔒 Security

Please report a vulnerability privately through the affected repository's **Security** tab ("Report a vulnerability") rather than in a public issue. Each repository's `SECURITY.md` has the details.
