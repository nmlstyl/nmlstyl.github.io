---
# Landing page for nmlstyl.art — redirects visitors to joeymariano.com/music,
# while carrying nmlstyl branding/metadata for link previews and crawlers.
# To turn this into a real site later, restore `layout: home` and add content below.
layout: null
sitemap: false
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>nmlstyl</title>

  <!-- Redirect humans to the music page (crawlers still read the metadata below) -->
  <link rel="canonical" href="https://nmlstyl.art/">
  <meta http-equiv="refresh" content="0; url=https://joeymariano.com/music">
  <script>location.replace("https://joeymariano.com/music" + location.search + location.hash);</script>

  <!-- Identity -->
  <meta name="description" content="nmlstyl — say it 'animal style.' Joey Mariano's audiovisual project: chip/synth/vapor-wave, surf rock, techno, and retro 80s textures, with guitar, graffiti, code, and pixel art.">
  <meta name="author" content="Joey Michalina Mariano">
  <meta name="keywords" content="chiptune, synthwave, vaporwave, guitar, 8bit, chip music, diy, graffiti, electronic, techno, surfrock, nes, sega genesis">
  <link rel="icon" href="/assets/favicon.ico" sizes="any">

  <!-- Open Graph -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="nmlstyl">
  <meta property="og:title" content="nmlstyl">
  <meta property="og:description" content="nmlstyl — say it 'animal style.' Joey Mariano's audiovisual project: chip/synth/vapor-wave, surf rock, techno, and retro 80s textures, with guitar, graffiti, code, and pixel art.">
  <meta property="og:url" content="https://nmlstyl.art/">
  <meta property="og:image" content="https://nmlstyl.art/assets/og-nmlstyl.png">
  <meta property="og:image:width" content="2475">
  <meta property="og:image:height" content="2475">

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="nmlstyl">
  <meta name="twitter:description" content="nmlstyl — say it 'animal style.' Joey Mariano's audiovisual project: chip/synth/vapor-wave, surf rock, techno, and retro 80s textures, with guitar, graffiti, code, and pixel art.">
  <meta name="twitter:image" content="https://nmlstyl.art/assets/og-nmlstyl.png">
</head>
<body>
  <p>Redirecting to <a href="https://joeymariano.com/music">joeymariano.com/music</a>&hellip;</p>

  <!-- Bio (for crawlers and any future build-out) -->
  <main hidden>
    <p>[ say it out loud as <strong>animal style</strong> &hellip; but drop the vowels when you write it out ]</p>
    <p>nmlstyl is Joey Mariano's audiovisual project: electronic music &bull; guitar &bull; graffiti &bull; code &bull; pixel art.</p>
    <p>The live show combines chip/synth/vapor-wave, surf rock, techno, instrumental hip hop, and retro 80s textures. Influenced by video game soundtracks, jazz professionals, and DIY punk, the performances offer a mix of nostalgic and contemporary sounds. Expect covers of popular songs with parts replaced by a game console, original music built from 90s puzzle-game samples, reinvented Pac-Man-style sound effects, Joey-style improvisation, retro guitar tones, and lush synth bass patches.</p>
  </main>
</body>
</html>
