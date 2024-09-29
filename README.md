![image](https://github.com/user-attachments/assets/414f57e3-238c-4959-868b-7c718074ada0)
-->THIS IS HOW THE PAGE LOOKS <--
# Photography.
Photography webpage using Html5 and CSS

CSS Styling:

Applied a modern font (Fredoka) from Google Fonts to enhance the aesthetics.
Utilized CSS properties like background-image, box-shadow, and rgba() for a visually appealing design.
Ensured responsive design by using relative units and positioning elements with absolute and fixed properties.
Checkbox Hack for Sidebar Menu:

Implemented a checkbox input element to toggle the visibility of the sidebar menu.
Used the :checked pseudo-class to change the sidebar's position when the checkbox is checked or unchecked, allowing the menu to slide in and out of view seamlessly. This provides a clean and interactive user experience without needing JavaScript.
css
Copy code
#check {
    display: none; 
} 
#check:checked ~ .sidebar_menu {
    left: 0; /* Show menu */
}
Hover Effects:

Enhanced user interaction by adding hover effects to menu items and icons, such as scaling icons and changing colors.
Implemented smooth transitions for hover effects using the transition property to improve the user experience.
Font Awesome Icons:

Integrated Font Awesome to utilize a variety of icons, enhancing the visual appeal of the menu and social media links.
Responsive Design Considerations:

Considered the layout's adaptability to different screen sizes, ensuring a user-friendly experience across devices.
