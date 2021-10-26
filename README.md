<h1>ASSIGNMENT 2:</h1>

<h2>Please find below the pointers that I have worked on as part of this assignment;</h2>

<h3>Important NOTE:</h3>
<b>* Since this is a single web page, all the anchor elements are pointing to the same webpage.</b><br>
<b>* Since there is no server side component to this webpage, all the forms in the webpage are using the "GET" method instead of the "POST" method, since "POST" won't be     	     supported.</b><br><br> 

1. Made a HTML only webpage with reference to the webpage included as part of the assignment. Below points describe the structure of the page in detail.

2. The HTML `<head>` element just contains the `<title>` of the page and a `<meta charset="UTF-8">` element. 

3. The main `<header>` of the page includes the below elements;
	* An `<img>` element to add the **MODERN** logo image.
	* A few `<a>` anchor elements to navigate to **Home**, **About**, **Featured** and **Contact** pages.
	* A "check notifications" button.
	* A login button created using `<input type="button">`.
	* Also used `<em>` element to emphasise on the heading.


4. I divided the HTML body further into <b>five</b> main sections;
   * <b>Section One</b>
     * First section of the page contains a form to filter out the apartments and buying, selling and renting options. Key elements used are:
       * `<header>` element to include the section header.
       * `<figure>` element to include the `<picture>` elemtent which are displayed on the page using `<img>` element.
       * `<a>` anchor elements have been used to redirect the user when then click on **Buy**, **Sell** or **Rent**.
       * `<form>` element is used to created a simple form which allows the user to add a filter criteria while searching for an apartment. Validations have been added to the            form so that the user cannot sumbit the form without populating any of the input fields.

   * <b>Section Two:</b>
     * In this section, the user can select the type of apartment and submit the request. The apartment selection is also a form where the user can select the apartment type and submit the request to the server. Key elements used are:
       * `<header>` element to include the section header.
       * `<form>` element is used to allow the user to select an aparment type. `<input type="radio">` is used in this form.
       
   * <b>Section Three:</b>
     * This section displays the featured apartments. Key elements used are:
       * `<header>` element to include the section header.
       * `<input type="image">` is used to make the featured apartment images act as an input element so that the user can click on the appropriate featured apartment to view them in detail.
	   * Also made use of a bit of Scalable Vector Graphics using `<svg>` element along with its `<circle>` element to make 3 dot diagram as shown in the sample assignment webpage.


   * <b>Section Four:</b>
     * In this section, the plans of the apartments are visible. Key elements used are:
       * `<header>` element to include the section header.
       * `<input type="radio">` so that the user can switch between the apartment plans of different apartment types.
       * `<img>` element to display the image of the apartment plan.
       * Used <b>Description List</b> elements `<dl>`, `<dt>` and `<dd>` to add some description about the selected apartment.

   * <b>Section Five:</b>
     * This is the final section. Key elements used are:
       * `<header>` element to include the section header.
       * `<input type="button">` to display a button that allows the user to view all the apartments.
       * `<figure>` element to semantically group all the media on this section such as images and video files.
       * `<video>` element inside the `<figure>` element to include the video file of this section.
       * `<picture>` element inside the `<figure>` element to include all the images of the section which are displayed using the `<img>` element.
      
5. The `<footer>` section of the page contains all the imprtant links, social media share buttons etc.. Key elements used are;
   * `<img>` element to display the logo image.
   *  `<a>` anchor elements to link the "Useful Links" and "Help" links.
   *  `<input type="image">` to add social media share buttons. 
