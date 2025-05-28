
# 1. web_test Intro.
 - This is a demo and template to create your own website using git, VS code, and github. 
 - You could skip the git and VS code and use the github web version directly to create your own website.

 - To use local dev., follow instructions 2 , 4, 5
 - To use web. dev., follow instructions 3 , 4, 5

# 2. Local dev. Instructions using git and VS code:
1. Download and install VS code studio 
2. Open terminal: MAC - command + space, type in terminal.  Windows - search terminal
3. Install Git:  sudo dnf install git-all
 - if that doesn't work: try
    
    git --version

    your computer may ask you to install git, which will take ~20 GB storage.

    or

    sudo apt install git-all

4. Copy URL of your repo - use SSH url
5. Clone your project to the local computer using the following command

    git clone your_url

6. Navigate to your project using VS code


## 2.1 Push changes to git ** 

1. In terminal, go to your folder. Follow the below command exactly.
2. git add .
3. git commit -m "update contents"
4. git push origin main

## 2.2 Don't have ssh-key?

1. ssh-keygen -t rsa -C "you@example.com" 

2. copy the key to your repo add public key   

## 2.3 Preveiw your change locally
1. Save all your changes in VS code

2. Go to your folder on computer ---> double click index.html



# 3. Web dev. using github directly

 - You may navigate to the github repo. and make changes online directly. Click on edit button, make any neccessary changes that you need. Then Commit changes with your messages. 

 - Add useful commit messages about what has changed, so you could find them later if you changed your mind.

## 3.1 Preveiw your change online

 - Where do I find my url?  your repo ---> Settings ----> Pages   

 - Save the URL in your bookmark and refresh it after you commit your changes. 

 - Use your saved webpage url, refresh your page after saving.  It takes about 30s to have the new change.

# 4. Both local and web dev. use the same change for the following.
## 4.1 Change color

 - Use index.css to change font color and background color.

 *Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.*
## 4.2 Change backgound picture

 - Update pictures in assesets folder. Consider to change favicon, planet.  Remember to use the same name and extension.

## 4.3 Change your description

 - Update index.html. Locate your description of any sub-field, update the sentences.

 *HTML, short for HyperText Markup Language, is the foundation of every webpage. It's a markup language used to structure and organize content on the web, defining elements like headings, paragraphs, images, and links.*

## 4.4 Update your resume or use other pdf file

 - Update the pdf file in assests directory
 - Update the pdf file name in the container class, index.html. 

 *Simply relace the pdf file by uploading a new pdf file, search pdf in index.html and locate the file name that is needed to be replaced.*

# 5. Publish your web

1. Navigate to your project on github. ----> Settings ---->Pages----->Branch (select main)

2. Wait about 30s and refresh the page, you should see the public url now.
  

# 6. References

- Properly cite any images used in your project.

- Cite any other references you have used and update the references.

Plastic Bottle Background:
https://earth.google.com/web

plastic bottle image:
https://www.google.com/search?sca_esv=c28d7f4a7239b712&rlz=1C5CHFA_enUS972US972&q=plastic+bottles&udm=2&fbs=AIIjpHxU7SXXniUZfeShr2fp4giZ1Y6MJ25_tmWITc7uy4KIeioyp3OhN11EY0n5qfq-zENwnGygERInUV_0g0XKeHGJBEXLz4R1Z33kknVKOo4klLIPY3HEx3TD4815xZz7czOhNl7zvOujyaegiZ-gB1z3Y5dG0D3ujIkwQSGAXzKG43IYv7IkNSYczKvaobZOg-kD57VDd0zAQSsWlWkGIoZ8Z28q5w&sa=X&ved=2ahUKEwiXser72caNAxWVCjQIHYB0GsIQtKgLegQIFBAB&biw=1425&bih=739&dpr=2&safe=active&ssui=on#vhid=pnlZi4CCwri8yM&vssid=mosaic

Code reference:

https://github.com/ndoherty-xyz/unemployables-portfolio-template

https://www.shaktiplasticinds.com/plastic-recycling-an-essential-solution-to-our-planets-plastic-waste-problem/ 

https://www.sciencedirect.com/science/article/pii/S2772397624000042

https://www.nationalgeographic.com/environment/article/plastic-pollution

https://www.unep.org/plastic-pollution#:~:text=Plastic%20pollution%20can%20alter%20habitats,t%20exist%20in%20a%20vacuum.


