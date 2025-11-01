<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 200" style="background:#48546A">
  <defs>
    <!-- Background code pattern -->
    <pattern id="codePattern" width="200" height="60" patternUnits="userSpaceOnUse">
      <text x="0" y="20" font-size="12" fill="#a3c4ff" font-family="monospace" opacity="0.25">
        const soon = "developing...";
      </text>
      <text x="0" y="40" font-size="12" fill="#c0e0ff" font-family="monospace" opacity="0.2">
        function launch() { return true; }
      </text>
    </pattern>

    <!-- Soft shadow filter -->
    <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="2" dy="4" stdDeviation="6" flood-color="#000" flood-opacity="0.4"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#codePattern)" />

  <!-- Centered Group -->
  <g transform="translate(300,100)" text-anchor="middle" dominant-baseline="middle">
    <!-- Arrow icon -->
    <polygon points="-110,-10 -90,0 -110,10" fill="#ffffff" filter="url(#softShadow)" />

    <!-- 3D Text -->
    <text font-size="72" font-family="Segoe UI, Roboto, sans-serif"
          font-weight="700" fill="#ffffff" filter="url(#softShadow)">
      Soon
    </text>
  </g>
</svg>
