# Design Guidelines

## Colour Scheme
- **Primary Color**: #0056b3 for the links(a)
- **Secondary Color**: #FFFFFF (white) for the  background
- **Accent Color**: #FFFFFF (white)
- **Text Color**: #000000(black) for general text to ensure readability

## Typography
- **Headings Font**: h1:"Roboto", "Arial", sans-serif; h2:"Lora", "Georgia",serif; h3:"Georgia", serif
    - **Font size**: h1:28px, h2:26px,h3:default
    - **Font weight**: bold
    - **Font style**: h2:italic h1,h3: default
    - **Font color**: black
- **Body Text Font**: "Arial", "Helvetica", sans-serif;
     - **Font size**:  18px
    - **Font weight**: Normal
    - **Font style**: Normal
    - **Font color**: black

## Layout and Spacing
- **Header**:
    - **Layout**: Flexbox with center alignment
    - **Padding**: 18px top and bottom
- **Image Container**:
    - **Layout**: Flexbox for column alignment, centered content
    - **Image Styling**: Border-radius of 50%, width and height of 100px (80px on mobile)
    - **Caption Styling**: Centered text, margin of 10px top and bottom
- **Profile and Education Containers**:
    - **Layout**: Flexbox for row alignment, spaced between items
    - **Gap**: 40px
    - **Padding**: 20px
    - **Skill Buttons**:
    - **Background Color**: Black
    - **Text Color**: White
    - **Hover Effect**: Background color changes to gray
- **Experience Items**:
    - **Background Color**: Inherit from parent
    - **Border**: 5px double black at the bottom
    - **Padding**: 10px bottom
    
- **Accessibility**:
    - **Contrast**: Ensured sufficient contrast between text and background for readability.

- **Media Queries**:
- **Mobile (max-width: 767px)**:
    - **Font Size: 16px for paragraphs**:
    - **Image Size**: Reduced to 80px for better fit
- **Tablets (min-width: 768px and max-width: 1199px)**:
    - **Font Size**: 14px for body text
    - **Image Container**:: Padding adjusted to 10px top and bottom
- **Large Desktop (min-width: 1200px)**:
    - **Font Size**: Increased to 22px for body text
- **Print**:
    - **Background**: None
    - **Text Color**: Black
    - **Image**: Hidden
    - **Skill Button**: Styled for visibility with black background and borders
    - **Footer**: Hidden in print


