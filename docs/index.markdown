---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: How to Generate Alt Text Using Gemini
---

## **What is Alt Text?**
Alt text, or ***alternative text***, is a descriptive element added to an image on website. It provides a brief description of an image, its context and information for those who cannot view the image, particularly the visually impaired. 

When a visually impaired person uses a screen reader to access a webpage, alt text is read aloud, providing users an alternate way to consume the image content. 


![image](images/examplealt.PNG)

## **Step-by-Step Guide**
1. Go to [Google Gemini](gemini.google.com) and sign in or create an account. Gemini Advanced is not required to generate alt text, but may help to create better descriptions.
2. Upload the image you would like to generate alt text for by clicking the upload image button in the search bar, as seen below.
![step2](images/step2.png)
3. In the prompt, write "Generate alt text for this image. Please provide a concise description."
4. Await the reply. Once you receive the generated alt text, you may continue to provide more instructions in order to create a better suited description, or add this alt text description to your website.  
![geminigif](images/gemini.gif)
5. As you can see in the generated examples above, the first description contained some false information as it said the score is "20 to 10" but there is no game currently being played in the image. However, the second description "An aerial night view of a football stadium with the Georgia Tech logo on the field." is suitable for alt text and would be added to my website.

## **Alt Text Best Practices**

<!-- Before using Gemini to help us generate alt text, we should first understand the dos and don'ts of alt text. Although Gemini might generate an accurate description of your image, the description might not make for good alt text.

Follow these guidelines when writing alt text. -->

- **Do not begin alt text with "image of" or "picture of".**
    -  A screen reader will inform the reader that an image is being described.
- **Keep descriptions short and concise.** 
- **Mark any images that do not convey information as a decorative image.**
- **Include any text in the image in your description.**
    - For instance, if the image contains a road sign, describe what the sign says in the alt text. 
- **For complex images such as graphs or charts, include a brief alt text that describes the basic properties of the image, followed by a long description that explains the essential information communicated by the image.**
- **Ensure your alt text makes sense in the context of your web page.**

## **Good vs Bad Alt Text**

What makes alt text "good" depends heavily on the context of your website. Consider the following image:

![image](images/hugging.jpg)

Suppose your webpage is a news site and the above image is part of a story about the aftermath of a devistating tornado. Here are some examples of good and bad alt text: 

### Helpful alt text
```
A distraught man hugs his daughter in front of collapsed walls and scattered debris from their house destroyed by a tornado.
```

### Ambiguous alt text
```
A man and a woman embracing near a demolished building.
```

It is important to provide Gemini with the appropriate context of your website before asking it to provide alt text for your website's images.

Make sure that you carefully read what Gemini generates. Large language models like Gemini can sometimes produce false or misleading information, so you must make sure Gemini is producing alt text that is accurate, useful, and inclusive. 

## **Conclusion**

Alt text has other uses besides aiding the visually impaired. When images on a website cannot load properly, the alt text is loaded in their place. Search engines also analyze the alt text on your website, so including relevant alt text can help improve your website's SEO! 

Since writing helpful alt text for every important image on your website can be a tedious process, some developers neglect alt text. 
Fortunately, Google's AI chatbot Gemini can help you quickly write alt text for your website!
