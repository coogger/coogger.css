[Join and Contact us on Discord](https://discord.gg/avmdZJa)


### Usage

#### Before

Download css files in your pc or server

```html
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1 user-scalable=no"/>

    <link
    rel="stylesheet"
    href="/path/to/styles/default.css"> 
    <!-- default css -->

    <link
    rel="stylesheet"
    href="/path/to/styles/general.css">
    <!-- general -->
    
    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/laptop-l.css" 
    media="(min-width: 1025px) and (max-width: 1440px)">
    <!-- laptop large -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/laptop.css" 
    media="(min-width: 769px) and (max-width: 1024px)">
    <!-- laptop -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/max.css" 
    media="(min-width: 1441px) and (max-width: 2560px)">
    <!-- 4k -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/mobile-l.css" 
    media="(min-width: 376px) and (max-width: 425px)">
    <!-- mobile large -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/mobile-m.css" 
    media="(min-width: 321px) and (max-width: 375px)">
    <!-- mobile medium -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/mobile-s.css" 
    media="(min-width: 0px) and (max-width: 320px)">
    <!-- mobile small -->

    <link
    rel="preload" 
    as="style"
    onload="this.rel = 'stylesheet'"
    href="/path/to/styles/tablet.css" 
    media="(min-width: 426px) and (max-width: 768px)">
    <!-- tablet -->
</head>

```