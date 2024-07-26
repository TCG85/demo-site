
# Instructions to Update the AI Art Gallery with Your Own Images

This guide will help you update the AI Art Gallery with your own images. Follow the steps below to replace the existing images with your own and ensure they are properly displayed on the website.

## Steps to Update Images

### 1. Organize Your Images

1.1 Prepare your images and organize them into the following categories:
- Characters
- Cityscapes
- Indoors
- Textures
- Styles

1.2 Ensure each image has a descriptive name. This helps with SEO and accessibility.

### 2. Resize Your Images

2.1 Resize your images to create thumbnail versions. Aim for a consistent size, such as 200x200 pixels.

2.2 Save the thumbnails with the suffix `_tn` to differentiate them from the full-sized images.

### 3. Add Your Images to the Project

3.1 Place your full-sized images and thumbnails into the appropriate folders:
- `images/characters/`
- `images/cityscapes/`
- `images/indoors/`
- `images/textures/`
- `images/styles/`

### 4. Update the HTML

4.1 Open the `index.html` file in your project.

4.2 Locate the sections for each image category. Each section is marked by an `<h2>` tag with the category name, such as `<h2>Unique Characters</h2>`.

4.3 Replace the existing `<img>` tags with your own images. Ensure you update the `src` attribute to point to your new images and update the `alt` attribute with a descriptive text.

Example:
```html
<div class="grid">
  <div><img src="images/characters/your_image_tn.jpg" alt="Description of your image" /></div>
</div>
```

### 5. Verify Your Changes

5.1 Open your `index.html` file in a web browser to verify that the images display correctly.

5.2 Check the layout and ensure all images are properly aligned and displayed in the intended sections.

### 6. Push Changes to GitHub

6.1 Commit your changes:
```sh
git add .
git commit -m "Updated gallery with new images"
```

6.2 Push your changes to GitHub:
```sh
git push origin main
```

## Additional Tips

- Use descriptive filenames for your images to improve SEO.
- Maintain a consistent naming convention for your images.
- Test the website on different devices to ensure responsive design.

By following these steps, you can easily update the AI Art Gallery with your own images and showcase your unique creations.
