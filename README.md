# WEB102 Prework – Sea Monster Crowdfunding

**Submitted by:** Patrick Manswell

**Sea Monster Crowdfunding** is a small web app that loads a list of “games,” displays summary stats at the top, and lets users filter, search, and browse by funding status.  

**Time spent: 6 hours total

---

## Required Features

The following **required** functionality is completed:

- [x] Dynamically load and display a list of games as “cards”  
- [x] Show total contributions, total amount pledged, and total number of games at the top  
- [x] Filter buttons for **All**, **Funded Only**, and **Unfunded Only**  

- [x] Highlight the top two most-funded games in their own containers  

---

## Optional Features

- [ ] Lazy-load images (`loading="lazy"`)  
- [ ] Responsive grid layout for game cards
- [ ] Live search bar that filters by game name as you type  

---

##[ Video Walkthrough](url)



*GIF created with [Loom](loom.com).*

---

## Notes

- Wrapped all DOM-manipulation code in a `DOMContentLoaded` listener to avoid `document is not defined` errors when testing locally.  
- Used `toLocaleString('en-US')` to format large numbers with commas.  
- Employed array methods (`filter`, `reduce`, destructuring/spread) for concise, readable logic.

---

## License

```text
Copyright 2025 Patrick Manswell

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
...
