# The history of Muslim scientists

The History Of Muslim Scientists project is a website that will bring you back to the middle ages and give you a better idea on what the middle we like. The website present information about one of the most influential people in the history of science. Yes! in the history of science. What if I told you that the Americas were not first discovered by Christopher Colombus, or Isaak Newton was not the first to talk about the three laws of motion or fo you know the muslim mechanical engineer that Leonardo Devinci grow up learning from his books? It is ok if you do not know, that is why you have this website. This project is created mainly to shed light on these people and inform the public about who they are and what are their contribution.<br>
Moreover, it can be useful to wide range of people who may feel the need to know this information such as, science and theology students, muslims who wanted to know more about their heritage, newly convert who are curious to know about the contribution of muslim scientists and how religion was a fuel for these people to excel as religion require them to seek knowledge and learn science. <br>
<br>
This a picture that show how the website appears on multiple devices:<br><br>
![picture that show how the website appear on different devices](/assets/readmeimages/projectondevices.png)
<br><br>

## Features <br>
We have many features available for our users to make browsing the website easy and enjoyable.'

### Exising Features

- Navigation
    - It is located at the top of the page, The navigation bar shows the name of the site that can be clicked and take you to the home page.
    - There is also a home button to help you return to the home page.
    - The is a _disciplines_ section that helps you navigate the different disciplines we have on the site.
    - Since the middle ages were named the golden ages for muslim scientists we have chosen a golden color to be the primary color of the site and thus it was chosed as a background color for the navigation bar.
    - The bar also have a _contact us_ and a _donate_ links for you to contact us and to donate to our cause.

![an image of the header](/assets/readmeimages/navigation.png)
<br>

- The Header
    - The header shows a picture of a mosque. the mosque picture was taken by my friend Mr Naas who owns the right to the picture. The picture is the inside of a mosque in Turkey.
    - Under the picture there is a short description of the site and what it provides.

![picture of the header of the home page](assets/readmeimages/header.png)
<br>

- Disciplines Sections
    - There are five disciplines on this site Mathematics, Physics, Chemistry, Medicine and Women in Science.
    - Each section shows multiple scientists in that field followed by an article that describes their life and their achievemnts. An example is shown in the folowwing pictures:

![mathematics page](assets/readmeimages/methematics.png)
![physics page](assets/readmeimages/physics.png)
![chemistry page](assets/readmeimages/chemistry.png)
![medicine page](assets/readmeimages/medicine.png)
![women in science page](assets/readmeimages/wis.png)
![example of content page](assets/readmeimages/content.png)

- Footer section
    - The footer also has a golden color background and it is at the bottom of the page.
    - It contains link to our social media platform for the users to connect with us and to learn more about the history of muslim scientists.

![footer image](assets/readmeimages/footer.png)

- Contact us section
    - The contact us section provide a way for website users to share their feedback and general questions with us.

![Contact us page image](assets/readmeimages/contactus.png)

- Donate section
    - This section is available so that our users can donate to our organisation to support our effort to spread the message and improve the site.
    - In the future, this section will also feature links to other organisations that support the goal so that our users can have many option to where they would like to donate.

![donate page image](assets/readmeimages/donate.png)

## Testing

* I testes this page on multiple browsers and it shows properly. I also added the css code to the _Autoprefixer_ website to add any vendor prefixes.
* I used the inspect function in Chrome to verify the responsiveness of the website on different screens.
* I tested all the links in the navigation page and they all work and connect to the other pages of the website. I also tested the external link and that they open on new tabs to improve the user experience.
* The donate form and the contact us form wor properly and their important field have to be filled before a submission is possible. Upon successfull completion, the user will be taken to a success pag to ensure the user that the form was submitted properly.
* I also tested the internal links from different pages to ensure that they all work.
<br>

## Bugs <br>

### solved bugs <br>

* When I deployed the project to Github Pages the background image did not show. I run multiple tests and finally found the issue. It was the path of the image. I added two dots in front of the path and the image was displayed.

 ```background-image: url('../images/background.jpg')```

* I also found another bug while testing for screen responsiveness. Although I used the media queries to adjust the width. It was not responsive and it did not behave as I wanted. After using the inspect tool and a consultation, I found that the problem was caused by the size of the images. I added a css styling to ensure that the images will also change size when the type of screen is changed. It fixed the problem.

### Unsolved bugs

At the moment there are no unsolved bugs.

## Validator Testing

* HTML validator

    * Fixed an error in the chemistry file as I used a ul inside a ul and it was supposed to be li for the list elements. Fixed the issue and no error were found after that.
    * In the contact page, I found an error in the input tag for message. I had to remove the required option and remove the placeholder and change the type to text. No errors were found after that.
    * In the donate page, I also changed the type of the message input to text. No errors were found after that.
    * In the index page, article tags were creating an issue as they require a heading. Removed the article tags and there were no errors after that.
    * In the mathematics page, I also removed the article tag and the there was no errors after that.

    ![HTML validator green bar showing no errors](assets/readmeimages/validator.png)

* CSS validator
    * There was no error in the CSS validator.

     ![HTML validator green bar showing no errors](assets/readmeimages/cssvalidator.png)

* Lghthouse tool (accessibility)

    This test was completed for all the pages and the results are below. One error appeared on all the tests and it is related to the antivirus I have on my laptop. It always include a javascript line in my code and I could not remove it. So, lighthouse finds it each time and give me an error of uhaving unused javascript. an image of that message will be provided.

    * <ins>Chemistry page</ins> <br>

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_chemistry.png) <br><br>
            
       - The results show 100% in accessibility so it has passed the test.

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_chemistry2.png)  <br><br>

       - This part of the test shows the potential savings that we can make in term of the time required to load the page. Lighthouse call it the render-blocking resources.
       - We cannot change those services as they are outside tools that were used to build the project so we do not have any control on how they are made. These include  _Googlefonts_ and _Bootstrap_, plus my Antivirus.

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_chemistry3.png)  <br><br>

       - "Enable text compression" This part of the result also include other potential savings and it is related to the antivirus.

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_chemistry4.png)  <br><br>

       - The "minify Javascript" is about the antivirus on my computer.
       - "Serve static assets" is about the images used. I already compressed all the images and used the webp version. Except for the background image. I found that the jpg format occupied less storage than the webp format so I used used the jpg format.
       - The "unused CSS" is for Fontawesome website.

    * <ins>Contact page</ins> <br>

       - The results were similar to previous page so we will not repeat the same the provided information. <br>

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_contact.png) <br>

    * <ins>Donate page</ins> <br>

       - The results were similar to previous page so we will not repeat the same the provided information. <br>

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_donate.png) <br>

    * <ins>Index page</ins> <br>

       - The results we similar except with the performance being only 96% here. This is die to the large image in the home page. An image of the message is added below. <br>

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_index.png) <br>
    ![lighthouse test result for chemistry page](assets/readmeimages/lh_index2.png) <br>

    * <ins>Mathematics page</ins> <br>

       - For the disciplines pages we will only run the mathematics page as they all have the same structure. <br>

    ![lighthouse test result for chemistry page](assets/readmeimages/lh_math.png) <br>

    

