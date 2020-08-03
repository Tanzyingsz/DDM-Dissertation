# Why and how digital storytelling affects the user experience on an e-commerce website - The case of RE:source, a sustainable B2C second-hand brand

# ACKNOWLEDGEMENTS

# ABSTRACT

# 1.INTRODUCTION

The main objective of this project is to explore the reason why storytelling affects user experience on e-commerce website and how storytelling achieve that. The dissertaton first draw the insights of digital storytelling from other researchers together, then explain how the theories work through case stuides. After the general discussion comes the detail introduction to the sustainbility ideas and structure design of RE:source. By incoporating the useful findings in research and studies, the RE:source website is built. Finally, ...interviews.

The output of this dissertation is a fully functional second-hand e-commerce website. The focus of the dissertation is digital storytelling which is largely shown on front-end. Hence, the back-end shopping functions like add-to-cart, payment APIs and product management system are made through Webflow, a website building a hosting service. Nevertheless, none template used. Every front-end parts are literally built from sketch.

The project is currently host under the domain https://re-source.live.

# 2.LITERATURE REVIEW

## 2.1 Storytelling

### 2.1.1 Start From the Origin: What Is Storytelling?

To understand digital storytelling, we should first start from the very basic - story. A story contains a series of information that makes up narrative. In history, various definations are set for story. "Narratives are stories", through storytelling, one can understand his own life better(Shankar et al,2001). Stories create the experience that fulfill the listener's desire of searching for emotions(Fournier, 1998). As for storytelling, it is the bring story to life.

Storytelling has been widely used becasue of it affects how people think and act. On one hand, science backup the crucial role of storytelling - the human brain is hardwired for stories. Neuroeconomist Zak discovered story will increase the release of neurochemical oxytocin, the so-called "love hormone" and dopamine which contribute a long-lasting and more accurate memory(Zak, 2013). Besides, human tend to mirror their experience to the speaker's. Hence, after listenting to the story, the customer will perform a higher level of empathy. On the other hand, the voice of the public support the importance of storytelling. In the 2017 report, storytelling was rated the most effective marketing tactics among 62% of B2B marketers. The number of B2C storytelling supporter was even higher (The Science of Storytelling (Infographic), 2017). It is said that people are 22 times more likely to memorize a fact when they are presented in the form of a story (Ochs and Capps, 2009). <br/>

### 2.1.3 Storytelling Structure

Storytelling benefits a brand in many ways. To begin with, storytelling remove the barrier of connecting to a brand. In the modern world, the information explosion feeds people with way too much noise (Miller, 2017). Luckily, storytelling is a powerful approach to create music out of noise, since it emphasize the main ideas and weaken irrelevant information. Well-choreographed story act like a map that leads the customer all the way through the product and services provided. In this case, the customer does not have to overload their mental capacity and can make a connection with a brand easily. Then storytelling convey the personality of a brand.<br/>

Not any random story will work as a persuasive brand story. Instead of talking merely about the brand itself, tell the story about the customer makes the customer care more (Miller, 2017). While Bragging about the quality of product or service is not the goal of a brand story, Establishing a stronger relationship between the brand and customer definitely is. The trick in storytelling is instead of showing the whole picture at the beginning, let the reader figure out the story on their own. As Andrew Stanton (2012), the world-famous film director once said in his TED: "Don't give them (the audience) 4, give them 2+2."<br/>

【为什么最终选了 SB7】
Some framework helps to structure a story that provides the better user experience, the previous study proposed frameworks like the persona-based model (Herskovitz, and Crystal,2010), the Hero’s Journey story framework (Campbell, 2008), story brand 7-Part framework (SB7 framework) (Miller, 2017) etc. Among which Miller's framework is the most comprehensive and easy to process for customers. Therefore this project plan to adapt Miller's work into practice. The SB7 framework proposes a 7-plot-points genuine story formula:<br/><br/>

(1) _A character_, specially refers to a hero acted by the customer
(2) _A problem to solve_. If the character stays in forever peace, the story cannot move on. Therefore a villain usually exists to push forward the plot. In order to find out the villain of the story, two levels of problems, namely external and internal problems are all considered.
(3) _A guide_. The one who helps the hero to conquer all problems and win. The brand itself acts as the guidance of the hero.
(4) _A plan_ that takes away consumer's confusion.
(5) _Call to action_, challenge the character to take an actual step that brings them from challenge back to a peaceful life.
(6) _A vision of tragic ending_ that warns the customer what might happen if they do not follow the lead of this brand.
(7) _The glorious success_ illustrates the bright future of trusting this brand.

<br/>RE:source project largely built the storyline based on SB7 framework, with two user cases considered, the buyer and the donor.

【structure， 提到 bait】

## 2.2 Ditial Storytelling

### 2.2.1 What is digital storytelling

The concept of digital storytelling first came up in the 1990s when the Center for Digital Storytelling began to held workshop that engage the audience who are willing to share their story.(StoryCenter, 2020) Later on, as the internet developed, many【添加引用】 have made an attempt to define digital storytelling. Nevertheless, they all end up consider digitral storytelling as a way to explain traditional storytelling through a mutlimedia way. Therefore, to understand digital storytelling, one should first define what storytelling is.

The key elements of a digital storytelling in this dissertation is stated as followed:

_Digital storytelling is web-based._ Usually, the forms of digital covers a wider range of technique and format. The multimedia in digital storytelling includes but not limited to text, video, audio and sound effect etc. In practical environemnt, ground-breaking works like interactive TV series "Black Mirror: Bandersnatch" and immersive game "Detroit: Become Human" had greatly expand the border of digital storytelling form. However, to narrow the concept, the term digital storytelling used in this dissertation covers only the web-based narratives, namely website.

_Digital storytelling is interactive._ The interactivity is actually the greatest difference between classic storytelling and digital storytelling(Handler Miller,2008). Since digital storyteling is web-based, human-computer interaction is included. In this case, the interactive nature of digital storytelling directly switch the user identity from an "audience" to a "participant." Unlike traditional media, such as books and movies, where information act as a one-way flow, user's activity will influence the content on digital storytelling medium. For example, when interacting with a digital storytelling website, users are expecting the system to provide feedback as soon as they input or change the parameters on page.

[ *Figure: interactive range slider*]

The old form of narrative follows a fixed linear manner while the storyline digital storytelling could be affected by the interaction between audience and materials provided【改】.

### 2.2.2 Why Digital Storytelling Affects User Experience?

【三个方面】

#### 2.2.3 How Digital Storytelling On A Website Works? The Secret Formula

**How to establish the environment of story? The usage of colour**

##### **How to show the influence? The power of data**

People are drawn to numbers. In the world full of uncertainty and scam, a static firm number offer user a sense of reliability and add counterweight to digital storytelling (Damodaran, 2017). Data in storytelling can convey information more vividly. For example, in the RE:source campaign that persuades people the importance of sustainability, the hard-hitting stats of how severe the environment has been damaged is more persuasive than pure descriptive paragraph."Every person in the UK produce 409kg waste annually which is roughly the weight of 4 giant pandas" is better than "There are many waste in the UK". People will get a quantitative sense of the waste and also feels the animal they cherished get hurt by their careless activity. Similarly, when it comes to stressing how an acitivity contribute to environment, "We have saved 235000 grams of waste already" sounds more impressive than "We saved the enviornment."

##### **How to hightlight the points? Typography and motion graphics helps**

Studies pointed out that web users tend to scan web pages than reading word by word (Morkes and Nielsen, 1997) Therefore a clear visual hierarchy and attention-grabbing design of the key story part becomes crucial. Typography and motion graphics together makes the scanning expereince easier and more understandable.

Typography act as one of the core building blocks for visual hierarchy. A proper text treatment will measurably affect user productivity and increase satisfaction in user experience(Boulton, 2009). Generally, the typographical hierarchy is dealing with contrast. It highlights the content that matters to the user most. Designers commonly create contrast between headings and body text through the adjustment of font size, weight, typeface and the whitespace in between letters. Since contrast contains the meaning of "difference", it is crucial to set distinct roles to fonts and their variants. And the role should be consistent within a website for a united user experience.

Motion graphics is an advanced version of visual design that combines animation and static images together. They act as visual aids of text content. The most commonly seen form is short footage that aims to help break down complex or abstract story. While human brain already proceeds visual content 60,000 times faster than text(3M Visual Systems Division, 2018), we are also more sensitive to moving objects(Beverley and Regan, 1980). That is to say, motion graphics not only improve the user interpretation speed on story but capture their attention at the same time. What's more And the role of motion graphics actually exceed a simple information deliverer: they also direct the user sight along a certain direction or indicate the hierarchy.

[Figure: arrow motion on hover, indicate the entrance of a secondary page][figure: looping motion graphics that directs user to next section]

> Morkes, J., & Nielsen, J., 1997. Concise, scannable, and objective: How to write for the Web.
> Boulton, M., 2009. A practical guide to designing for the web. Mark Boulton Design Limited.
> 3M Visual Systems Division, 2018. Polishing your presentation. [online] web.archive.org. Available at: http://web.archive.org/web/20001102203936/http%3A//3m.com/meetingnetwork/files/meetingguide_pres.pdf [Accessed 3 Aug. 2020].
> Beverley, K. I. and Regan, D., 1980 ‘Visual Sensitivity to the Shape and Size of a Moving Object: Implications for Models of Object Perception’, Perception, 9(2), pp. 151–160. doi: 10.1068/p090151.

‌

interaction and narrative
responsiveness

> Damodaran, A., 2017. Narrative and numbers: the value of stories in business. Columbia University Press.

## 2.3 Case Studies: Digital Storytelling On E-commerce Websites

### 2.3.1 Etsy - The global marketplace

As a sustainable brand, Etsy introduce digital storytelling to convey user its value and build up a enjoyable user experience.
At the end of the Etsy main page, there is a hyperlink leads to "our wonderfully weird story." Within the link is a text-heavy but clean "About" page (https://www.etsy.com/uk/about). While large-scale text takes up half of the space, motion graphics with abundant empty space takes up the rest. All the keywords in paragraph are highlighted with underline, clicking any of them will reveal a hidden section of explaining motion graphic. From the visual design perspective, the low saturation colour is comforting and consistent. The hand-drawing style graphics fits the vintage and creative setting of the brand. From the interaciton perspective, the clicable keywords brings user entertainment because the hidden sections are surprising. Also, the persuasive data shown act as powerful evidence of how influence Etsy is and affects user's emotion towrards Ebay - according to "Bandwagon effect", the user is more willing to be part of the community when they see a large amount of people had already done the same (Leibenstein, 1950).

[Figure: Screenshot of Etsy "ABOUT" page - the usage of motion graphicss and data]

After user scroll down the page, they will come to the darker seciton with call-to-action button embedded. The visual cues of this part stands out thanks to the large area of dark blue background. While scrolling this part, the motion graphics on the right hand side change according to the content, just like a step guide that informs the users where they are. The animation expresses the process more intuitively than pure text. It helps to ease the anxiety of getting lost in pages and keep users on the page. Also, this section follows "the rule of odds" - odd number of objects in an image is more interesting and appealing compare to even number objects (Zhang and Multiexposure, 2012). The easy-to-follow steps shows the user how to be a seller or buyer and get access to help.

[Figure: Screenshot of Etsy "ABOUT" page - the usage of motion graphicss and data]

> Leibenstein, H.,1950. Bandwagon, snob, and Veblen effects in the theory of consumers' demand. The quarterly journal of economics, 64(2), pp. 183-207.

> Zhang, H. and Multiexposure, W.K.C.G.D., 2012. Composition. IEEE transactions on image processing, 21(4).

### 2.3.2 Dopper - The reusable bottle

Dopper built an extremely immersive digital storytelling experience.(https://dopper.com/our-mission) Generally, the Dopper story follows the SB7 storytelling framework and prove that the framework works.

Following the description in 2.1.3 section,he user who read through the page is the hero while Dopper act as the guide.

Firstly, Dopper place a bait and establish an undersea theme through its sea-like 3D environment and text description. The scroll-down interaction is a clever metaphor of diving into the sea - as user browsing through the page, the background change from above sea level to underwater and the colour get darker just like the dim light in deep sea. The beginning part is also a bait for potential customer, since it plants a question in user mind "What did single-use plastic do to our crystal clear water?"

Then large scaring number of plastic waste jump into the page, while disgusting tiny plastic pieces floating in the background. These part thow out the enviorment problem that the user and Dopper will sovle together and is also the a vision of tragic ending if user refuse Dopper bottles. During this section, users might experience a certain level of shock, regret and will probably expect to find a way out in the rest content.

Thankfully, Dopper immeditaly present its product as a solution to the terrifying situation.The full-angle presentation of water bottle along with copyright sentences targeted to the previous problems. Meanwhile, the background lightup and makes the scrolling experience more relaxed.

Furthermore, Dopper emphasize its mission and impact by listing its action and educational programms. Interestingly, the rule of odds appear once again. The slowly increasing number of the plastic waste reduction vividly express the idea that Dopper is continuously making its contribution. Most importantly, the page introduce interaction into its process - when users slide the range bar, they will be able to see the impact they will have on the enviroment with buying Dopper product. This part illustrate the bright and meaningful future where the user will contribute to the greater good. The impluse of purchasing a Dopper bottle is unstoppable.

Finally, the button to the shopping section float up, waiting for the user action. "Our oceans will thank you." and "contribute to these cool things" increase the user proud and esteem ever more. The whole cycle of digital storytelling ends thoroughly.

### 2.3.3 Analysis on case studies

What the two cases has in common:

1. They both had a clear visual hierarchy and empasize the call-to-action part with deep colour.
2. They heavily relied on statistics to convey the user their value and impact.

# 3. RE:source DESIGN RESEARCH

# 4. RE:source WEBSITE (METHODOLOGY & EXECUTION)

The goal of the story presented on RE:source is to convince the potential donor and buyer that they can make a difference to enviornemnt by answering the call for action on RE:source platform. To achive that goal, the approach on "Our-mission" page is to first

【Inspiration】

【odd number rule （lucky dip 卡片数量）】

【count up】

【hidden section】

【g 和 kg】

## 4.1 The Design Process

_Figure: RE:source site map_

# 5. CONCLUSION

## 5.1 Evaluation of the storytelling in RE:source

### 5.1.1 Method

To elicit information about how the user experience on the RE:source storytelling goes, 5 semi-structured interviews were carried out. Questions were focused on the user experience regarding the usability of the website, the emotional reaciton towrads the story and the overall feelling on engagement【加一个理论引用 e.g. Measuring storytelling Engagement】.

### 5.1.2 Participants and Procedure

5 students participated in this study. All of them are Chinese students currently studying or about to study in the UK. Every interviewee has no previous interaction with the website. This is to make sure the result is purely based on their first impression on the project. Participants were first asked to finsih 2 simple tasks : 1.Get to the last step of the donation process, the donation form 2.Get to the payment page of one product. Then they free to explore the "our-mission" storytelling page. After browsing through the whole website, the interview is conducted. All interviews were recorded.

### 5.1.3 Results

【采访结果】

### 5.1.4 Discussion and Future Development

The interviews reveal that...

The study also indicates that...

Based on the feedbacks from interviews, the future version of RE:source might need a English to Chinese translation function, to help the target user navigate with the website.

# BIBLIOGRAPHY

> StoryCenter. 2020. [online] Available at: <http://www.storycenter.org/resources.html> [Accessed 14 July 2020].

> Shankar, A., Elliott, R., & Goulding, C., 2001. Understanding consumption: Contributions from a narrative perspective. Journal of marketing Management, 17(3-4), pp. 429-453.

> Fournier, S., 1998. Consumers and their brands: Developing relationship theory in consumer research. Journal of consumer research, 24(4), 343-373.

> Miller, D., 2017. Building a StoryBrand: Clarify your message so customers will listen. HarperCollins Leadership.

> Handler Miller, C. (2008). Tales from the Digital Frontier: Breakthroughs in Storytelling. [online] Writersstore.com. Available at: https://www.writersstore.com/tales-from-the-digital-frontier-breakthroughs-in-storytelling/ [Accessed 14 Jul. 2020].

> Blanka, G. and Reisdorf, B. C. (2012). The participatory web: A user perspective on Web 2.0. Information, Communication & Society, 15(4), 537-554.

# Appendix 1 - User Interview Outline

---

# 备用语句

steps can be outlined as follows:
Another common term that narrows the concept is Interactive Digital Storytelling (IDS).
Figures measurements and statistics
