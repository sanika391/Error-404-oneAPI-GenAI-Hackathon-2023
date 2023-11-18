# oneAPI-GenAI-Hackathon-2023 - Hack2Skill

#### Team Name - Error 404
#### Problem Statement - Revolutionary AI-Infused Retail Platform
Leverage the power of GenAI to transform the retail industry. Participants are challenged to create a cutting-edge retail website that integrates Intel® Developer Cloud and the Intel® AI Analytics Toolkit, delivering a personalised and intelligent shopping experience.
#### Team Leader Email - sanikachavan1806@gmail.com

### A Brief of the Prototype:
Prototype Description:
The prototype involves a web-based retail interface where users can interact with a 360-Degree Viewer Component powered by the Intel® Developer Cloud.

- Homepage: Users land on the homepage and can explore various products.

- Product Details:Clicking on a product opens a detailed view where users can view specifications and details.

- 360-Degree Viewer:Within the detailed view, a 360-degree viewer allows users to interactively rotate and view the product from every angle.

- Zoom and Specifications:Users can zoom in for a closer look. Zooming triggers the display of relevant specifications in real-time, eliminating the need to scroll or navigate to a separate section.

- Contrast with Static Images:The dynamic 360-degree viewer contrasts with static image platforms like Amazon or Flipkart, providing a more engaging and efficient user experience.

- Integration with Intel® Developer Cloud:The 360-Degree Viewer Component is seamlessly integrated with the Intel® Developer Cloud, leveraging GenAI technology for a personalized and intelligent shopping experience.

- Analytics Integration:The Intel® Developer Cloud connects to the Intel® AI Analytics Toolkit, providing insights into user behavior and preferences.
This prototype enhances the overall shopping experience by providing an immersive 360-degree view, efficient information retrieval, and personalized recommendations, all powered by the Intel® Developer Cloud.

  
### Tech Stack: 
   TECHNOLOGIES:
- 1.Intel® Distribution of OpenVINO™ toolkit
- 2.Intel® Geti™ software platform
- 3.Intel® oneAPI unified programming model
- 4.Intel® RealSense™ technology
- 5.Intel vPro® platform
- 6.Intel® Core™ and Intel Atom®
- 7.Intel® Xeon® Scalable processors
- 8.Intel® Core™
- 9.Intel® Smart Edge
- 10.Developer resources for AI in retail
- 11.360 degree Product viewer
- 12.intel AI DevCloud
- 13.Natural Language Processing(NLP)
- 14.Mongo DB
- 15.Django
- 16.OpenAI ChatGPT 4.0
   
   
### Step-by-Step Code Execution Instructions:
  Building a website with a 360-degree product viewer involves various technologies and steps. Below are simplified instructions considering the technologies mentioned. 

Step-by-Step Code Execution Instructions:
1. Clone the Repository - Clone your project repository to your local machine:
     ```bash
     git clone <repository-url>
     cd <project-folder>
     ```
2. Set Up Environment - Ensure you have Python and Django installed.
   pip install django

3. Create Django Project and App - Create a Django project and app.
     ```bash
     django-admin startproject myproject
     cd myproject
     python manage.py startapp myapp
     ```
4. Set Up MongoDB - Install and set up MongoDB.
     ```bash
     pip install djongo
     ```
5. Create Models - Define your models in the `models.py` file of your app.

6. Configure Settings:- Update the Django project settings to use Djongo for MongoDB.

7. Implement 360-Degree Viewer:
   - Integrate a 360-degree viewer library (e.g., Three.js) into your project.
   - Include the necessary scripts and styles in your HTML templates.

8. Connect to Intel® DevCloud:
   - Use the Intel® DevCloud for AI development and testing.
   - Follow the documentation to set up your project on DevCloud.

9. Implement AI Features:
   - Integrate Intel® Distribution of OpenVINO™ for AI inference.
   - Use Intel® oneAPI and OpenAI ChatGPT 4.0 for intelligent interactions.

10. Implement NLP:
   - Integrate Natural Language Processing using the OpenAI ChatGPT 4.0 model.
   - Utilize NLP for conversational interfaces and user interactions.

11. Run the Django Development Server:
   - Start the Django development server.
     ```bash
     python manage.py runserver
     ```

12. Open the Website:
   - Open your web browser and go to `http://localhost:8000` to view your website.

13. Test the 360-Degree Viewer:- Test the 360-degree viewer functionality by uploading products with 360-degree images.

14. Test AI Features:- Test the integration with Intel® DevCloud for AI inference and OpenAI ChatGPT 4.0 for NLP.


Compared to existing websites like Flipkart and Amazon, the proposed website's 360-degree product viewer and AI functions have the following advantages:

1. Improved Product Visualization:
-Benefit: Customers may interact with products from every perspective thanks to the immersive 360-degree product viewer.
Comparatively, most websites today just provide static photos, which makes it difficult for customers to thoroughly examine things.

2. Higher User Involvement-
Benefit: The 360-degree viewer's dynamic and interactive features keep consumers interested, making for a more pleasurable and memorable purchasing experience.
Comparatively, static information on traditional websites could make it difficult to keep consumers interested.

3.Customized Purchasing Process:
Advantage: Intelligent interactions and personalized product recommendations are made possible by AI technologies like NLP and Intel® Distribution of OpenVINOTM.
Comparison: The suggested solution uses sophisticated AI to provide more precise and customized suggestions, whereas the websites that are already in use employ recommendation engines.

4.Effective Information Obtaining:
Benefit: Instant access to comprehensive product information is made possible by zoom-integrated specifications in the 360-degree viewer, which saves consumers time searching for specifications.
Comparatively, on modern websites, comprehensive specs could require readers to scroll down or visit a different section.

5.Integration of Cutting-Edge Technology:
Benefit: The website's integration with OpenAI ChatGPT 4.0, Intel® oneAPI, and Intel® DevCloud demonstrates its dedication to utilizing cutting-edge technologies.
Comparison: The suggested website incorporates a greater range of cutting-edge technology for a more intelligent user experience, whereas current websites use AI. 

6.Making a Statement with a 3D Immersion:
Advantage: The 360-degree viewer's 3D immersive experience is what makes the website stand out and offers a special and cutting-edge feature.
Comparatively, such sophisticated visualisation features might not be present on traditional webpages.

7.NLP for Worldwide Accessibility:
Benefit: The website's Natural Language Processing (NLP) capabilities enable language barriers to be overcome, hence expanding its global audience.
Comparatively, traditional websites might not offer as much linguistic diversity.


### Future Scope:
   
1. Scalability:
   
- Architecture for Growth: To accommodate growing traffic, the prototype makes use of load balancing techniques, cloud infrastructure, and Intel® DevCloud.
- Auto-scaling Policies: By utilizing auto-scaling policies, the website can optimize performance during periods of high traffic by dynamically adjusting resources in response to demand.

2. Future Aspects:
   
- Integration of Intel® Technologies: The prototype makes use of several Intel® technologies, such as Intel® oneAPI, Intel® RealSenseTM technology, and Intel® Distribution of OpenVINOTM, to guarantee compatibility with upcoming developments in hardware and software capabilities.
- Cutting-Edge AI Integration: Integrating with OpenAI ChatGPT 4.0 shows a dedication to maintaining the leading edge of conversational AI and natural language processing, opening the door for future developments in interactional AI.
- The incorporation of a Sustainable Shopping Tracker is a strategic move to portray the platform as a trailblazer in sustainability practices, in line with emerging trends in eco-conscious consumption.

3.Business Value:

- Improved Customer Engagement: The 360-degree viewer and AI-powered features improve customer interaction, which raises client happiness and loyalty.
- Personalized Shopping Experience: By accommodating individual tastes and raising conversion rates, the application of AI for personalized recommendations gives businesses a competitive edge.
- Worldwide Accessibility: The platform's global reach is increased by using Natural Language Processing (NLP) for language translation, which opens up new markets and demographics.
- Differentiation via Innovation: The platform's cutting-edge AI integration and 3D immersive experience set it apart, generating a USP that can draw in tech-savvy and discriminating clients.
- Intel® Partnership: Working together with a pioneer in innovation and technology, such as Intel®, gives the platform more legitimacy and confidence. This collaboration may draw in IT enthusiasts and companies searching for dependable and innovative solutions.
- Data-Driven Decision Making: By providing the company with insightful data, the analytics engine linked with Intel® DevCloud facilitates data-driven decision-making for marketing, inventory control, and customer engagement strategies.

4. Upcoming Development and Extension:
   
- Flexibility in Response to New Technologies: The well-thought-out and flexible architecture makes it simple to adjust to new technologies. The platform can quickly incorporate new developments as they become available, such as better AI models or upgraded technology.
- Constant Improvement: The platform is kept current and competitive in the ever-changing e-commerce market by frequent updates and feature improvements that are driven by customer input and technology breakthroughs.
- engagement Between the Community and Developers: Promoting ongoing improvement and positioning the platform as an innovation hub requires keeping up with industry trends and fostering engagement with the developer community.

  
5. Long-Term Sustainability:
- Environmentally Friendly Projects In addition to attracting environmentally sensitive customers and bolstering the platform's long-term viability, the Sustainable Shopping Tracker showcases a dedication to long-term sustainability.
- Expandable Infrastructure for Upcoming Development: Utilizing scalable infrastructure, such as cloud services and Intel® technologies, guarantees that the platform can withstand long-term expansion and growing demand.


In summary, the produced prototype offers scalability, business value, and a platform for ongoing innovation in the ever-changing e-commerce industry, in addition to meeting present technology needs.



























