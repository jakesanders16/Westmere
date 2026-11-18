# Westmere Strategy Group , standalone local project

This is your full website source with the revised CEO page, your four supplied photos, and the rainy-noir / coffee-shop color direction. You do not need Lovable credits or a Lovable account to run it locally.

## Requirements
- Node.js 20+ (Node 22 LTS recommended)
- npm
- Internet access for the first `npm install` to fetch project dependencies

## Run on macOS
1. Extract the ZIP.
2. Open Terminal and move into the project folder. If it is in Downloads:
   `cd ~/Downloads/westmere-athlete-connect-main`
   Or type `cd ` (with a trailing space), drag the extracted project folder into Terminal, and press Return.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed in Terminal (usually `http://localhost:5173`).

Keep Terminal open while previewing. Press Control+C in Terminal to stop the server.

## Build
Run `npm run build` to create a production build. `npm run preview` previews that build locally.

## Notes
- This local preview does not automatically change the existing public Lovable URL.
- To publish independently, deploy the project to a hosting provider that supports Vite/TanStack Start and configure the production build/output for that provider.
- The homepage inquiry form submits through FormSubmit to `westmerestrategy@gmail.com`. On first use, FormSubmit sends an activation email to the inbox; click its confirmation link before relying on live submissions. Test the form from the deployed website after activation.
- The marquee ticker animation is preserved.
