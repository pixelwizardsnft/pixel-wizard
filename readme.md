![SVG Size](https://img.shields.io/badge/SVG%20Size-61kb-brightgreen)

![SVG-min Size](https://img.shields.io/badge/SVG--min%20Size-45kb-brightgreen)

# Pixel Wizards

A magical and wise collection of 2222 interactive animated wizards. Made from scalable vector graphics, animated with CSS and made interactive with JavaScript. Each wizard comes with a particular interest in a crypto token on which he can share his wisdom.

## File structure according to use
Each pixel wizard is composed on real time out of multiple files. When using `"image" ` value from the metadatafile it references to `wizard.svg`. When using `"animation_url"` the metadatafile references to `wizard.html`.
```
wizard.json
├── wizard.svg
└── wizard.html
│   ├── wizard.webmanifest
│   ├── static_assets/
│   │   ├── png256/
│   │   │   └── wizard.png
│   │   ├── png256/
│   │   │   └── wizard.png
│   │   ├── sounds/
│   │   │   └── q.wav
│   │   │   └── w1.wav
│   │   │   └── w2.wav
│   │   │   └── e.wav
│   │   │   └── r.wav
│   │   │   └── err.wav
```

## Authors

- [@berny-art](https://www.github.com/berny-art)


## Demo

- [IPFS](https://ipfs.io/ipfs/bafybeidwo4kicq35xnvmbaynl334uif26phmmk63sxncn76rhkyyo4ll6i/2222.html)
- [StargazeZone (NFT Marketplace)](https://www.stargaze.zone/m/pixelwizards)