# Waifu Pics API (Laravel)

A simple Laravel-based wrapper around the public Waifu Pics image API.  
This project was built as a portfolio piece and is now archived.

It provides clean API endpoints that fetch and return random anime images from SFW and NSFW categories.

---

## Overview

This application acts as a backend proxy to the Waifu Pics API, returning JSON responses containing image URLs. It is built with Laravel and designed to be lightweight and easy to run locally.

---

## Requirements

- PHP 8.x
- Composer
- Node.js & npm

---

## Installation

Clone the repository:

```bash
git clone https://github.com/PursDios/Waifu_Pics.git
cd Waifu_Pics

Install PHP dependencies:

composer install

Install frontend dependencies:

npm install
npm run build

Create environment file:

cp .env.example .env

Generate application key:

php artisan key:generate

Start the local server:

php artisan serve

The API will be available at:

http://127.0.0.1:8000
Example Endpoints

SFW example:

GET /api/sfw/waifu

NSFW example:

GET /api/nsfw/neko

Responses return JSON containing a direct image URL provided by the Waifu Pics service.

Notes

This project is archived and no longer actively maintained.

It was created as a demonstration of API integration and Laravel backend structure.
