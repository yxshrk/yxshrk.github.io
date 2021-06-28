Title: Travel Blog
#### Video Demo:  <https://www.youtube.com/watch?v=tlmYaglnRQ8>
#### Description:
Hi my name is Yash and I am from Singapore. I created this travel blog website where users can create accounts and register, login and use the functions available.
Users are able to share travel blogs on this site and can view travel blogs shared by other users that have visted countries. Each user has a unique username and password as an account is required to access the website. Users can register if required by providing a username, password
and a confirmation of their password as designed in the register.html page. The login page shows a background of Singapore city, which is the country I reside in, displaying scenic views of the city that would be perfect for travellers that want to
explore beautiful places on earth. It gives users the impression that they can find wonderful places to explore through this travel blog website, thus encouraging them to use it. Once users have logged in, they are brought to the homepage that is the result of rendering the index.html template.
The index.html page shows a list of all the different travel blogs that people have submitted. These people are other users on the platform itself. The homepage compiles all the travel blogs that have been submitted on the platform and displays it to the user,
like a social media platform page.

The index page serves as the homepage listing blogs from all the other users and allowing the user to interface with other parts of the website. Each user is able to view submitted travel blogs through the index page.
Each blog features a title listing the city and country that the traveller visited that was formatted in the index.html file. In addition to this, the name and clickable instagram handle of the user that submitted the travel blog is available for other users to see.
Below this, the actual blog is contained in the form of a description of the traveller's experiences at the place of visit. Finally below that, there is a link that enables viewers to see images of the specific place that the traveller visited,
through the creation of an image search engine in the index.html file. In application.py, all the elements of the blog inclusive of the country, city, description, name and instagram handle are apended into a list titled blogs in the form of a dictionary containing details specific to each blog.
These are then addded into the index.html file and are thus displayed on the homepage. The background image of the page features the city of Monaco which is an extremely lush and luxurious city that provides a nice backdrop for the main page.
I designed the textbox containing all the different travel blogs in a manner that would make it transparent, enabling users to see the city of Monaco through the textbox itself. I feel that this makes my website more aesthetically pleasing to the eye
which is the reason why I implemented this feature.


Next comes the add_blog.html page whereby users are able to add a blog to the main page for other users to see. This page features a form whereby users enter the country they visited, specific place in the country they visited, a description of their
travel experiences and their names as well as instagram handles which allows users to learn more about their content. In application.py, I had added a list of all the countries in the world that users can choose from in the form of an options bar when filling out
the specific country that they visited. This reduces the chances of ambiguity in blogs and unauthentic travel blog experiences that I am therefore able to have more control over. Getting the users to fill in all these fields not only allows the travel blogs
to be more authentic and reliable, but also allows me to implement sophisicated features such as the image search engine as I can obtain the name of the specific place from the blog database that the form fills up and format it into clickable links for users
to interact with. The same concept also applies to the Instagram page finder that employs the search engine to find the specific profile of the user that posted the blog. This allows frequent travel bloggers to be able to promote their content through
the travel blog website. I self-searched and taught myself how to add the background images on the pages and arrange the pages to appeal aesthetically to users. The website is simple in design but I do believe that it fulfills it's fundamental purpose.
The additional features such as the smart image finder and instagram page loader make my website more user friendly which in turn enables a better user experience to be achieved.

The TravelDestinations.html file features a page that shows travel recommendations to users of the site that I formatted myself. The top shows a young woman enjoying herself in Paris, which sets the mood for the website as one that encourages people to find
happiness through travel and enrich themselves when exploring the world. Thereafter, there are a few places that I have listed that I recommend people take trips to, providing descriptions of the places listed for users to learn more. At the end of the page,
there is a link for users to visit an external page where they can learn more about the top places in the world to visit that they can hopefully add to their list of travel destinations. I made this page to enable it to become easier for users to conduct research on places to visit
as they can gather all the information from one website rather than using several others and having to compile all the information.

The application.py file contains all the python code required to run the website in addition to helpers.py. Application.py imports flask, SQL and all the other necessary functions to make each section of the website run. SQL queries are conducted on
databases storing the data of users through application.py, in order to be able to utilise it to make the website run. This applies to the register, login and add blog functions on the website that require databases to run. Apart from that, application.py ensures that
responses to the form are valid in order to ensure that users add authentic blogs to the website in addition to ensuring that users create and use legitimate accounts to access the website. This improves the overall credibility and security of the website. Helpers.py renders the apology
template if users enter invalid responses and that users are logged in when they want to use the features of the website.



our README.md file should be minimally multiple paragraphs in length, and should explain what your project is, what each of the files you wrote for the project contains and does, and if you debated certain design choices, explaining why you made them. Ensure you allocate sufficient time and energy to writing a README.md that you are proud of and that documents your project thoroughly. Be proud of it!