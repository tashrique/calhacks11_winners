**1. Install dependencies**
```
npm install
```

**2. Run dev server**
```
npm run dev
```

**3. Edit config**
```
src/app/resources/config
```

**4. Edit content**
```
src/app/resources/content (or content-i18n for localization)
```

**5. Create blog posts / projects**
```
Add a new .mdx file to src/app/[locale]/blog/posts or src/app/[locale]/work/projects
```

# **Features**

-- [Once UI](https://once-ui.com)
- Automatic open-graph and X image generation with next/og
- Automatic schema and metadata generation based on the content file
- Responsive layout optimized for all screen sizes
- Timeless design without heavy animations and motion

## **Content**
- Render sections conditionally based on the content file
- Enable or disable pages for blog, work, gallery and about / CV
- Generate and display social links automatically
- Set up password protection for URLs

## **Localization (NEW)**
- Magic Portfolio now supports localization with the next-intl library
- See more info in resources/config.js
