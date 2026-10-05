Sucaya — Portfolio Design System

1. Product Identity

Name: Sucaya
Role: Full-Stack Developer & Robotics Developer

Design Direction

Portfolio menggunakan gaya Newsprint Editorial: tegas, teknis, terstruktur, dan berkarakter.

Visual menggabungkan nuansa koran klasik dengan identitas developer modern:

High-contrast black & off-white

Grid editorial yang kuat

Typography serif untuk headline

Sans-serif untuk interface

Monospace untuk metadata teknis

Sharp corners, tanpa rounded card

Border hitam sebagai elemen struktur

Aksen merah hanya untuk highlight penting

Layout asimetris untuk menampilkan proyek

Informasi padat tetapi tetap mudah dipindai

Design system ini mengikuti prinsip Newsprint yang menggunakan grid, tipografi dramatis, border eksplisit, dan zero-radius components. fileciteturn0file0L33-L50

2. Visual Direction

Core Concept

Building Software & Robotics Systems

Portfolio harus terasa seperti technical publication, bukan landing page SaaS generik.

Karakter visual:

AUTHORITATIVE
TECHNICAL
EDITORIAL
MINIMAL
STRUCTURED

Hindari:

Gradient

Glassmorphism

Soft shadow

Rounded card

Excessive animation

Warna berlebihan

Layout 50/50 yang terlalu generik

Gunakan:

Hard borders

Strong typography

Editorial columns

Black/white contrast

Red accent

Technical metadata

Dense information hierarchy

3. Color System

Token

Color

Usage

Background

#F9F9F7

Main background

Foreground

#111111

Text & borders

Muted

#E5E5E0

Divider

Accent

#CC0000

Highlight / CTA

Neutral 100

#F5F5F5

Hover

Neutral 400

#A3A3A3

Muted text

Neutral 500

#737373

Metadata

Neutral 600

#525252

Secondary text

Neutral 700

#404040

Secondary heading

Aksen merah digunakan secara hemat, terutama untuk label penting, CTA, hover, dan status tertentu. fileciteturn0file0L57-L80

4. Typography

Display

Playfair Display

Digunakan untuk:

Hero headline

Project title

Section heading

Large editorial statement

Body

Lora

Digunakan untuk:

Deskripsi

About

Project explanation

Long-form content

UI

Inter

Digunakan untuk:

Navigation

Button

Label

Navigation

Metadata

Technical

JetBrains Mono

Digunakan untuk:

Tech stack

Project metadata

Version

Date

Statistics

Code-related information

Font stack tersebut mengikuti sistem Newsprint pada source design. fileciteturn0file0L83-L96

5. Typography Scale

Hero
5xl → 6xl → 9xl

Section
4xl → 5xl

Project Title
2xl → 3xl

Body
sm → lg

Metadata
xs

Headline utama menggunakan line-height ketat dan tracking yang rapat untuk menciptakan karakter editorial yang kuat. fileciteturn0file0L98-L116

6. Shape & Border

Radius

border-radius: 0;

Tidak ada rounded corner.

Semua komponen menggunakan bentuk geometris tajam.

Border

border: 1px solid #111111;

Untuk divider utama:

border-bottom: 4px solid #111111;

Border bukan sekadar dekorasi. Border menjadi bagian utama dari sistem grid.

7. Layout

Container

max-width: 1280px
margin: auto
padding: 16px

Desktop menggunakan sistem 12-column grid.

┌──────────────────────────────────────────────┐
│                 HEADER                       │
├───────────────┬──────────────────────────────┤
│               │                              │
│     HERO      │       INTRO / PROFILE        │
│               │                              │
├───────────────┴──────────────────────────────┤
│                PROJECTS                      │
├───────────┬───────────┬──────────────────────┤
│ PROJECT 1 │ PROJECT 2 │ PROJECT 3            │
├───────────┴───────────┴──────────────────────┤
│                TECH STACK                    │
├──────────────────────────────────────────────┤
│                  CONTACT                     │
└──────────────────────────────────────────────┘

Grid mengikuti pendekatan 12 kolom dan collapsed borders dari design system. fileciteturn0file0L309-L333

8. Homepage Structure

Header

Header bersifat sticky.

SUCAYA                         ABOUT
FULL-STACK & ROBOTICS          PROJECTS
                               CONTACT

Metadata kecil:

VOL. 01 | DEVELOPER PORTFOLIO | 2026

Navigation menggunakan uppercase, monospace/sans-serif, dan tracking lebar.

9. Hero Section

Hero harus menjadi elemen paling dominan.

Headline

BUILDING
SOFTWARE
& ROBOTICS.

Subheadline:

Full-Stack Developer & Robotics Developer
Building practical systems across software,
hardware, automation, and IoT.

Layout:

┌──────────────────────────────┬───────────────┐
│                              │               │
│ BUILDING                     │ FULL-STACK    │
│ SOFTWARE                     │ ROBOTICS      │
│ & ROBOTICS.                  │ DEVELOPMENT   │
│                              │               │
└──────────────────────────────┴───────────────┘

Gunakan split asimetris, bukan 50/50.

10. About Section

Label:

01 / ABOUT

Headline:

Software meets hardware.

Isi menjelaskan Sucaya sebagai developer yang mengerjakan:

Full-stack application

REST API

Database

Flutter

Robotics

Arduino

ESP32

IoT

Automation

System integration

Gunakan drop-cap pada paragraf pembuka untuk mempertahankan karakter editorial. fileciteturn0file0L275-L304

11. Featured Projects

Section label:

02 / SELECTED PROJECTS

Gunakan layout editorial dengan ukuran card yang tidak seragam.

Project 01

WEB ABSENSI

FULL-STACK WEB

Deskripsi:

Sistem absensi berbasis web untuk pengelolaan data kehadiran secara terpusat.

Technology:

HTML
CSS
JavaScript
PHP / Flask
MySQL

Project 02

ROBOT PENGANTAR BARANG

ROBOTICS / IOT

Deskripsi:

Robot autonomous untuk membantu proses pengantaran barang dari satu lokasi ke lokasi lain.

Technology:

Arduino
ESP32
C/C++
Motor Driver
Sensors
IoT

Project ini menjadi featured project utama karena menggabungkan software, hardware, automation, dan system integration.

Project 03

WEB KESEHATAN

FULL-STACK WEB

Deskripsi:

Platform web untuk pengelolaan informasi dan layanan kesehatan secara digital.

Technology:

HTML
CSS
JavaScript
Tailwind CSS
Flask
MySQL

12. Project Card

Struktur card:

┌────────────────────────────────────────────┐
│ FIG. 01                                    │
│                                            │
│ WEB ABSENSI                                │
│                                            │
│ Attendance Management System               │
│                                            │
│ ────────────────────────────────────────── │
│                                            │
│ HTML · JS · FLASK · MYSQL                  │
│                                            │
│ VIEW PROJECT →                             │
└────────────────────────────────────────────┘

Card:

border: 1px solid #111

border-radius: 0

Background #F9F9F7

Padding 24px

Hover menggunakan hard offset shadow

box-shadow: 4px 4px 0 #111;
transform: translate(-2px, -2px);

Hard shadow dan sharp card mengikuti interaction pattern Newsprint. fileciteturn0file0L231-L247

13. Tech Stack Section

Label:

03 / TECHNOLOGY

Gunakan grid padat.

┌──────────────┬──────────────┬──────────────┐
│ FLUTTER      │ PYTHON       │ FLASK        │
├──────────────┼──────────────┼──────────────┤
│ PHP          │ JAVASCRIPT   │ TAILWIND     │
├──────────────┼──────────────┼──────────────┤
│ MYSQL        │ ARDUINO      │ ESP32        │
├──────────────┼──────────────┼──────────────┤
│ REST API     │ IOT          │ ROBOTICS     │
└──────────────┴──────────────┴──────────────┘

Setiap item menggunakan border dan monospace label.

14. Capability Section

Gunakan inverted section.

BACKGROUND: #111111
TEXT: #F9F9F7

Headline:

FROM IDEA
TO SYSTEM.

Capabilities:

01  FRONTEND DEVELOPMENT
02  BACKEND & API
03  DATABASE DESIGN
04  ROBOTICS
05  IOT
06  SYSTEM INTEGRATION

Minimal satu section utama menggunakan inverted black/white treatment sesuai design direction. fileciteturn0file0L300-L307

15. Contact Section

Label:

04 / CONTACT

Headline:

LET'S BUILD
SOMETHING USEFUL.

CTA:

VIEW GITHUB
CONTACT ME

Primary button:

background: #111111;
color: #F9F9F7;
border: 1px solid #111111;

Hover:

background: #F9F9F7;
color: #111111;

Button menggunakan uppercase dengan tracking lebar dan minimum touch target 44px. fileciteturn0file0L197-L229

16. Footer

Footer menggunakan editorial metadata.

SUCAYA
FULL-STACK & ROBOTICS DEVELOPER

VOL. 01
PORTFOLIO EDITION · 2026

GITHUB
LINKEDIN
EMAIL

Bottom line:

© 2026 SUCAYA — BUILT WITH CODE & CIRCUITS.

17. Texture

Background menggunakan subtle dot-grid.

Tujuannya memberi tekstur seperti kertas tanpa mengganggu readability.

background-image:
url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='4' height='4' viewBox='0 0 4 4'%3E%3Cpath fill='%23111111' fill-opacity='0.04' d='M1 3h1v1H1V3zm2-2h1v1H3V1z'%3E%3C/path%3E%3C/svg%3E");

Gunakan texture secara halus. Jangan sampai portfolio terlihat seperti dokumen fotokopi yang sedang marah. fileciteturn0file0L152-L185

18. Image Treatment

Project images menggunakan grayscale secara default.

filter: grayscale(100%);

Hover:

filter: grayscale(50%) sepia(50%);

Untuk project robotics, foto robot dapat digunakan sebagai visual utama.

Tambahkan caption:

FIG. 02 — DELIVERY ROBOT PROTOTYPE

Gaya grayscale dan figure caption mengikuti mandatory editorial treatment. fileciteturn0file0L288-L299

19. Motion

Animation harus cepat dan mekanis.

Gunakan:

transition: all 200ms ease-out;

Interaction:

Button → color inversion

Card → hard shadow

Link → red underline

Image → subtle scale

Navigation → red hover

Icon → black/white inversion

Hindari:

Bounce

Floating animation

Blur transition

Parallax berlebihan

Smooth organic motion

Motion philosophy mengikuti sistem Newsprint yang menekankan interaction cepat dan mekanis. fileciteturn0file0L339-L369

20. Responsive

Desktop

≥ 1024px

Gunakan:

12-column grid

Asymmetric layout

Vertical dividers

Large typography

Multi-column project layout

Tablet

768px – 1023px

Kurangi:

Headline size

Column count

Padding

Mobile

< 768px

Layout menjadi satu kolom.

┌──────────────────────┐
│ HEADER               │
├──────────────────────┤
│ HERO                 │
├──────────────────────┤
│ ABOUT                │
├──────────────────────┤
│ PROJECT 01           │
├──────────────────────┤
│ PROJECT 02           │
├──────────────────────┤
│ PROJECT 03           │
├──────────────────────┤
│ TECHNOLOGY           │
├──────────────────────┤
│ CONTACT              │
└──────────────────────┘

Tetap pertahankan:

Sharp corners

High contrast

Border

Horizontal divider

Uppercase metadata

Responsive strategy ini mengikuti aturan source design untuk collapse grid dan mempertahankan karakter visual di mobile. fileciteturn0file0L398-L438

21. Accessibility

Semantic HTML

Gunakan:

<header>
<nav>
<main>
<section>
<article>
<footer>

Gunakan heading secara hierarkis:

H1
 ├── H2
 │    └── H3
 ├── H2
 │    └── H3
 └── H2

Keyboard

Semua interactive element harus dapat diakses dengan keyboard.

Focus:

focus-visible:outline-none
focus-visible:ring-2
focus-visible:ring-neutral-950
focus-visible:ring-offset-2

Images

Semua gambar memiliki alt.

Icon-only button wajib memiliki:

aria-label=""

Accessibility requirements mengikuti semantic HTML, keyboard navigation, focus state, dan ARIA guidance pada design system. fileciteturn0file0L441-L470

22. Implementation Stack

Recommended:

Frontend
Flutter Web / React

Styling
Tailwind CSS

Backend
Python Flask

Database
MySQL

Icons
Lucide

Deployment
Linux + Nginx

Version Control
Git + GitHub

Untuk implementasi React, design source merekomendasikan React modern dengan reusable component patterns dan utility merging. fileciteturn0file0L501-L509

23. Component Architecture

components/
├── layout/
│   ├── Header
│   ├── Footer
│   └── Section
│
├── ui/
│   ├── Button
│   ├── Badge
│   ├── GridCard
│   ├── Divider
│   └── IconBox
│
├── portfolio/
│   ├── Hero
│   ├── About
│   ├── ProjectCard
│   ├── ProjectGrid
│   ├── TechStack
│   ├── Capabilities
│   └── Contact
│
└── texture/
    ├── DotGrid
    └── NewsprintTexture

Prinsip:

Design token terpusat

Component reusable

Minimalkan one-off styling

Gunakan semantic naming

Pertahankan responsive behavior

Pisahkan content dari presentation

24. Final Design Principle

Portfolio Sucaya harus terasa seperti:

        NEWSPAPER
             +
      ENGINEERING
             +
        ROBOTICS
             +
          CODE

Bukan sekadar:

"Hello, I'm a developer."

Tetapi:

SUCAYA

FULL-STACK DEVELOPER
+
ROBOTICS DEVELOPER

BUILDING SOFTWARE,
HARDWARE,
AND SYSTEMS.

Design Keywords

EDITORIAL
TECHNICAL
SHARP
AUTHORITATIVE
MINIMAL
HIGH-CONTRAST
STRUCTURED
MECHANICAL

Primary objective: membuat portfolio yang dalam beberapa detik langsung menunjukkan siapa Sucaya, apa yang dibangun, dan kemampuan teknis yang dimiliki tanpa membebani pengunjung dengan ornamen yang tidak berguna.