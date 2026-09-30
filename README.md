<svg width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Aurora Gradient -->
    <linearGradient id="dheetiMainGrad" x1="10" y1="10" x2="90" y2="90" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#7A5CFF" />
      <stop offset="52%" stop-color="#A855F7" />
      <stop offset="100%" stop-color="#FF7EB0" />
    </linearGradient>

    <!-- Glass Specular Highlight -->
    <linearGradient id="dheetiGlass" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.4" />
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0" />
    </linearGradient>

    <!-- Intellect Spark Gradient -->
    <linearGradient id="dheetiBeacon" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#7EDCC4" />
      <stop offset="100%" stop-color="#4DE1D0" />
    </linearGradient>
  </defs>

  <!-- Squircle Base with Border -->
  <rect x="4" y="4" width="92" height="92" rx="26" fill="url(#dheetiMainGrad)" stroke="rgba(255,255,255,0.45)" stroke-width="2.5" />
  <rect x="6" y="6" width="88" height="42" rx="24" fill="url(#dheetiGlass)" />

  <!-- D Spine -->
  <rect x="24" y="23" width="9" height="54" rx="4.5" fill="#FFFFFF" />

  <!-- Outer Wing of 'D' (Ledger Page) -->
  <path d="M 28 23 H 50 C 69 23, 78 35, 78 50 C 78 65, 69 77, 50 77 H 28 V 68 H 49 C 61 68, 68 60, 68 50 C 68 40, 61 32, 49 32 H 28 Z" fill="#FFFFFF" fill-opacity="0.94" />

  <!-- Inner Dynamic Page Fold -->
  <path d="M 37 36 H 48 C 58 36, 62 42, 62 50 C 62 58, 58 64, 48 64 H 37 Z" fill="#FFFFFF" fill-opacity="0.25" />

  <!-- Beacon / Intellect Spark -->
  <path d="M 52 42 Q 52 50, 44 50 Q 52 50, 52 58 Q 52 50, 60 50 Q 52 50, 52 42 Z" fill="url(#dheetiBeacon)" />
  <circle cx="52" cy="50" r="1.8" fill="#FFFFFF" />
</svg>
