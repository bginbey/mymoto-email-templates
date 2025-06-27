# Banner Composite Image Instructions

## Image Requirements

To fix the email rendering issues in Outlook and Gmail, you need to create a single composite image that combines all the banner bottom elements.

### Image Specifications

- **Filename**: `banner-bottom-composite@2x.png`
- **Width**: 1072px (displayed at 536px in email)
- **Format**: PNG with transparency support
- **Location**: Save to `/assets/images/`

### Elements to Include in Composite

The composite image should include these elements from the original design:

1. **Gradient Background**
   - Start: #006268 (top)
   - End: #008077 (bottom)
   - Rounded corners at bottom (32px radius)

2. **MyMoto Rewards Logo**
   - Position: Centered at top
   - Include proper spacing from torn paper edge

3. **App Device Image**
   - Position: Below logo
   - Should extend to bottom edge

4. **Torn Paper Effect**
   - Position: At the top edge
   - Should overlap with the light blue section above

### How to Create in Figma

1. Select the entire banner bottom section in your Figma design
2. Include all layers:
   - Gradient background
   - Logo
   - App device mockup
   - Torn paper effect
3. Export as PNG at 2x resolution
4. Ensure the image has proper rounded corners at the bottom

### Alternative: Using Image Editing Software

If exporting from Figma doesn't capture all effects:

1. Export each element separately:
   - Gradient background (with rounded corners)
   - Logo
   - App device
   - Torn paper effect
   
2. Combine in Photoshop/Sketch:
   - Create canvas: 1072px wide
   - Add gradient background
   - Place torn paper at top
   - Add logo with proper spacing
   - Position app device at bottom
   - Export as PNG

### Testing

After creating the image:
1. Replace the placeholder path in the template
2. Test in email clients
3. Verify rounded corners display correctly
4. Check that the torn paper aligns with the section above