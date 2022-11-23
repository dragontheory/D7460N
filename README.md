#foo {color: red}
<style>
 ol {
   list-style: none;
   counter-reset: item;
 }
 li {
   counter-increment: item;
   margin-bottom: 5px;
 }
 li:before {
   margin-right: 10px;
   content: counter(item);
   background: lightblue;
   border-radius: 100%;
   color: white;
   width: 1.2em;
   text-align: center;
   display: inline-block;
 }
 </style>

<h1 align="center"><img src="assets/images/logo.svg" width="50%" /></h1>

```

 ________    ________   __     ______     ______  ___     ___      ___    ___ ___
/\   ___ `\ /\____   \ /  `\  /  ____\  /' ____ `\\   -  /\  \    /\  \  /\  \\  \
\ \  \  /\ `\/___/   //  _  \/\  \___/_/\  \  /\  \\    " .\  \   \ \  \ \ \  \\  \
 \ \  \ \ \  \  /   //  /_\  \_\   ___ `\\  \ \ \  \\  \ .     \   \ \  \ \ \  \\  \
  \ \  \___\  \/   //\______   __  \_/\  \\  \___\  \\  \  " .  \   \ \  \___\  \\  \
   \ \________/\__/ \/_____/\__\/\_______/ \________/ \__\  \ \__\   \ \________/ \__\
    \/_______/\/_/         \/__/\/______/ \/_______/ \/__/   \/__/    \/_______/ \/__/

```

### End-users:

<ul>
  <li>Professional/minimal look/feel</li>
  <li>Optional configurable themes (light, dark, system)</li>
  <li>Optional configurable layouts (horizontal, vertical)</li>
  <li>Optional configurable UI density</li>
  <li>Compatable with all screen sizes</li>
  <li>Desktop keyboard accessible</li>
  <li>Mobile touch/swipe controls</li>
  <li>Fullscreen/Zen mode</li>
</ul>

### Developers:

<ul>
  <li>Pure CSS UI Template</li>
  <li>Single Page Application (SPA)</li>
  <li>Progressive Web Application (PWA)</li>
  <li>JAMstack architecture</li>
  <li>W3C/WHATWG standards compliant</li>
  <li>Vanilla (no dependencies)</li>
  <li>Minimal nesting (flat)</li>
  <li>Minimal/no classes</li>
  <li>Data agnostic</li>
  <li>JS Framework agnostic</li>
  <li>Media platform agnostic (responsive)</li>
  <li>Browser agnostic</li>
  <li>No build process</li>
  <li>No compile process</li>
  <li>No server required</li>
  <li>Web Storage API</li>
  <li>Modern CSS:
    <ul>
      <li>:has() pseudo-class</li>
      <li>@layer (optional third party integration)
      <li>container queries
      <li>custom elements
      <li>custom properties
    </ul>
  </li>
</ul>

### Developement Priciples:

<ul>
  <li>Minimal clean markup</li>
  <li>Minimal clean look/feel</li>
  <li>Least Power:
    <ol>
      <li>Can it be done in HTML?</li>
      <li>Can it be done in CSS?</li>
      <li>Can it be done in JS?</li>
      <li>etc.</li>
    </ol>
  </li>
  <li>Separation of Concerns:
    <ul>
      <li>Data from UI</li>
      <li>Presentation from middle-tier</li>
    </ul>
  </li>
</ul>
