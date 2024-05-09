# Kerri
Simple template with HTML and CSS only.

## Components
### 1.Home
![home](https://github.com/NoorseenQandil/Kerri/assets/70522199/4a92b02f-e2d9-459d-b35e-3534490ee5b2)

### 2.About
![about](https://github.com/NoorseenQandil/Kerri/assets/70522199/f363b5ad-92b7-4c9b-aa2f-a3587d0bd974)

### 3.Overlayer
![layer](https://github.com/NoorseenQandil/Kerri/assets/70522199/16b9a272-d0a0-4929-a380-24ffe55b93ac)

### 4.Blog
![blog](https://github.com/NoorseenQandil/Kerri/assets/70522199/56218103-f92c-45e4-80f3-8e6e85a7a782)

## Hints
#### - Section1: Home
  - Consists of 2 parts: The first part includes Kerri logo image and navbar links. The second one includes main caption that consists of Title, caption and two buttons.
  - Use Float property and set left to its value to put the logo image in navbar on the left side.
    ```
      #home .navbar img{
       float: left;
      }
    ```
  - Use Float property and set right to value to put the navbar links on the right side.
  - Use list-style property and set none to its value to remove the list style put by default.
  - Its important to use clear with float.
  - Use text-align property and set center to its value to put the caption content in the center.
  - Use grouping to make the two buttons the same padding and border values.
    ```
       #home .caption .btn1 , #home .caption .btn2{
        padding: 10px 20px;
        border-radius: 50px;
        border: 1px solid #fff;
      }
    ```
#### - Section2: About
 - Consists of 2 sides: The left side includes image. The right one includes 2 title, short paragraph and one button.

#### - Section3: LightBox
 - This section consists of one image in background.
 - Use background-attachment property and set fixed to its value to make it scroll when scroll page.
 - Set fixed height value for this section.
   ```
     #overlay{
        height: 400px;
        background-image: url('../images/blog-3.jpg');
        background-size: 100% 100%;
        background-attachment: fixed;
      }
   ```
#### - Section4: Blog
  - This section consists of three parts.
  - Each one includes one image, title and paragraph for description.
  - Put the width of each section is 33.333% or use calc() CSS method to calculate width.
  - Use Float property to put the three parts on the same line.
  - Use Clear property with float.
  - To make each image in circle shape, Use border-raduis property and set its value to 50%.
    ```
     #blog .blog-item{
        float: left;
        width: calc(100% / 3);
        text-align: center;
        padding: 20px;
        }
    ```
## Live Demo
Experience the Tabs Project in action! Click the link below to access the live demo:

[Live Demo] (https://noorseenqandil.github.io/Kerri/)
Feel free to interact with the project, browse through different jobs, and explore the user-friendly interface. The live demo provides a hands-on experience to see the Tabs Project in action.

## Contributing
If you have suggestions or find issues with the template, feel free to open an issue or create a pull request. Contributions are welcome!

## Contact
If you have any questions, feedback, or suggestions, please feel free to reach out to us at NourseenQandil@gmail.com We value your input and would love to hear from you!
