# Slideshow Image Setup Guide

## How to Add New Slideshow Images

### Step 1: Add Images to the Slideshow Folder
1. Place your new slideshow images in: `images/slideshow/`
2. Recommended image names:
   - `intro-to-asher.png` (your personal photo)
   - `school-projects.png` (academic work showcase)
   - `hunch-projects.png` (NASA HUNCH projects)
   - `personal-projects.png` (personal coding projects)
   - Add more as needed: `robotics-team.png`, `coding-workspace.png`, etc.

### Step 2: Recommended Image Specifications
- **Format**: PNG or JPG
- **Dimensions**: 1920x1080 or similar widescreen ratio
- **File Size**: Under 2MB for faster loading
- **Content**: High-quality photos that represent each project category

### Step 3: Update Slideshow Data (Optional)
If you want to add more slides beyond the default 4, edit the `slideshowData` array in `index.html`:

```javascript
const slideshowData = [
    // Add new slides here
    {
        image: "images/slideshow/your-new-image.png",
        fallback: "images/default-fallback.png",
        alt: "Description for accessibility",
        title: "Your Slide Title",
        description: "Brief description of the slide content"
    }
];
```

### Current Slideshow Images Needed:
- [ ] `images/slideshow/intro-to-asher.png` - Your personal/professional photo
- [ ] `images/slideshow/school-projects.png` - Academic work showcase
- [ ] `images/slideshow/hunch-projects.png` - NASA HUNCH projects display
- [ ] `images/slideshow/personal-projects.png` - Personal coding projects

### Suggested Additional Images:
- Robotics team photos (Team 930)
- Coding workspace/setup
- Project demonstrations
- Achievement photos
- School events
- Professional headshots

The slideshow will automatically fallback to the original logo images if slideshow images aren't found, so your site will work perfectly while you collect better photos!
