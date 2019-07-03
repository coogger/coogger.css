### Usage

#### Before

Download css files in your pc or server

```html
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1 user-scalable=no"/>
    <link rel="stylesheet" href="path/to/styles/default.css">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/general.css" 
    media="(max-width: 2560px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/laptop.css" 
    media="(max-width: 1024px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/laptop-l.css" 
    media="(max-width: 1440px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/tablet.css" 
    media="(max-width: 768px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/mobile-l.css" 
    media="(max-width: 425px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/mobile-m.css" 
    media="(max-width: 375px)">
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="path/to/styles/mobile-s.css" 
    media=" (max-width: 320px)">
</head>

```