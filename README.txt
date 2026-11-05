LAKBAY · Local & International Travel Explorer

Cloudflare Pages deployment:
1. Extract this ZIP.
2. Open Cloudflare Dashboard > Workers & Pages > Create > Pages > Upload assets.
3. Upload index.html and deploy. No build command is required.

This version adds a visible Local · Philippines / International selector.
Local preserves the existing island group > region > province directory.
International includes a searchable starter list of 10 countries and suggested travel hubs.
The international list is a starter directory, not a complete itinerary database.


vNext update: Added a Travel checklist page with separate Local and International preparation lists, progress tracking, custom tasks, mark-all-complete and reset controls. Checklist progress is stored in this browser using localStorage.


City directory update:
- Added a city selection directory under each province.
- Added the 16 National Capital Region cities directly under Luzon > National Capital Region (NCR), since NCR has no provinces.
- Added 149 city entries using the Philippine Statistics Authority PSGC cities list as the administrative reference.
- City-specific attractions and itineraries are marked as pending where they have not yet been curated; existing province-level attractions remain available.
