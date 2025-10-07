# Smart India Hackathon Workshop

## Register Number:212222040143
## Name: NAUSHEEN FATHIMA A
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
Core Idea: AYUSH-VRIKSHA (The AYUSH Tree of Knowledge)
Immersive Learning: Move beyond static images and text by using a gamified 3D virtual environment where users can freely explore and interact with realistic, rotatable 3D models of plants.

Centralized Knowledge Hub: Serve as a validated and structured digital library that provides comprehensive botanical, medicinal, and cultivation details for each herb.

Accessibility and Outreach: Bridge the gap of physical garden access, making traditional herbal knowledge available to students, practitioners, and the general public worldwide via web and mobile platforms.

Guided Exploration: Offer Virtual Tours and advanced Search/Filter capabilities to facilitate structured study and targeted research based on medicinal uses, regions, or AYUSH properties.


## Proposed Solution / Architecture Diagram
The solution for the Virtual Herbal Garden, named **AYUSH-VRIKSHA**, is structured around the following key points:

### I. Core Platform & Technology

* **Immersive 3D Environment:** Development of a **cross-platform virtual garden** accessible via web and mobile, utilizing a robust 3D rendering technology (like Three.js or Unity/WebGL).
* **Modern Stack:** Implementation using a high-performance **React/Next.js** frontend and a scalable backend (Node.js/Python) with a **PostgreSQL** database to manage structured botanical data.
* **Optimized Assets:** Focus on creating and integrating **high-fidelity, yet optimized, 3D models** (GLB/GLTF format) for efficient loading and interactivity.

### II. Interactive Content & Data

* **Realistic 3D Interaction:** Users can select any plant in the virtual garden to access an **Interactive 3D Model** that allows for **rotation, zooming, and close inspection** from all angles.
* **Validated Data Hub:** Each plant entry features a **Comprehensive Information Page** detailing:
    * **Botanical Data:** Scientific name, family, and native habitat.
    * **AYUSH Properties:** Traditional names, medicinal uses, specific parts used, and Ayurvedic properties (*Rasa, Virya, Vipaka*).
    * **Cultivation & Safety:** Methods of cultivation, harvesting, and safety/contraindications.
* **Multimedia Integration:** High-quality **images, educational videos** (showing traditional preparation or growth), and **audio descriptions** are integrated to enhance the learning experience.

### III. Navigation & Usability

* **Advanced Search & Filter:** Includes a powerful search engine and **dynamic filtering** capabilities based on criteria such as:
    * Medicinal use (e.g., "Anti-diabetic," "Respiratory support").
    * Geographical region (e.g., "Himalayan," "Coastal").
    * AYUSH system or specific traditional property.
* **Thematic Virtual Tours:** Provides **pre-defined, guided tours** through the garden, highlighting plants related to specific themes (e.g., "Immunity Trail," "Plants for Digestive Health") for structured exploration.

### IV. User Personalization

* **Personalized Accounts:** Users can register to save their progress and personalize their experience.
* **Bookmarking/Favorites:** Allows users to save favorite or currently studying plants to a **"My Herbal Shelf"** for quick access.
* **Private Notes:** A feature allowing students and practitioners to **take and save private study notes** linked directly to specific plant profiles.
* **Social Sharing:** Tools for easily sharing plant information and links on social media to promote awareness.




## Use Cases
I. Educational and Study Purposes (Students & Researchers)
Visual Identification & Study: The user needs to quickly identify a plant like Tulsi by its physical appearance and visually explore its structure from all angles for educational purposes.

Feature Used: Interactive 3D Model.

In-Depth Property Analysis: A student must retrieve and verify the traditional properties (e.g., Rasa, Virya) and botanical data of a herb for academic research.

Feature Used: Detailed Information Hub and Validated Data Source.

Structured Curriculum Following: A user requires a guided path to learn about all the common herbs related to a specific health system, like herbs for respiratory health.

Feature Used: Thematic Virtual Tours.

II. Practitioner and Research Needs
Targeted Medicinal Search: A practitioner needs to filter the entire database to find all plants that are "anti-diabetic" and whose primary "part used is the stem bark."

Feature Used: Advanced Filter Options (by medicinal use and plant part).

Habitat and Regional Cross-Reference: A user is sourcing a herb and needs to identify all validated species that grow naturally in the "Coastal Region" of India.

Feature Used: Advanced Filter Options (by geographical region).

Personalized Note-Taking: A user needs a private space to take research notes or observations specific to Giloy and save them within the platform for future reference.

Feature Used: Notes Feature and User Accounts.

III. General Public and Accessibility
Discovery and Awareness: A curious user wants to simply explore the virtual garden to learn interesting facts and traditional uses of common herbs they might encounter.

Feature Used: Interactive 3D Exploration and Audio Descriptions.

Cultivation Guidance: A hobbyist wants practical information on the ideal soil type, climate, and harvesting methods for a particular kitchen herb.

Feature Used: Detailed Information Hub (Cultivation section) and Multimedia Integration (Videos).

Knowledge Sharing: A user discovers a fascinating herb and wishes to share its scientifically backed profile with friends or family on social media.

Feature Used: Social Sharing Functionality.


## Technology Stack
Technology Stack (In Points)
3D Rendering: Three.js with React-Three-Fiber (for WebGL-based interactivity) OR Unity/Unreal Engine (for higher fidelity and dedicated mobile/desktop versions).

Frontend/Client: React or Next.js (for robust, fast, and SEO-friendly user interfaces).

Backend API: Node.js (Express) or Python (Django/Flask) (for scalable API development and business logic).

Database: PostgreSQL (for reliable and structured storage of validated botanical and user data).

3D Modeling & Design: Blender and Adobe Substance Painter (for creating and texturing optimized, realistic 3D assets).

Asset Storage: AWS S3 or Google Cloud Storage (for hosting large multimedia files, videos, and 3D models).

Search & Caching: Elasticsearch/Algolia (for powerful filtering and search) and Redis (for speeding up data access).

Deployment & Hosting: AWS Amplify/EC2 or Vercel/Netlify (for efficient, scalable hosting and content delivery).


## Dependencies
Validated Data Source: Access to accurate and authenticated data on medicinal plants (botanical names, chemical constituents, uses, etc.) from AYUSH Ministries/Institutions is crucial.

High-Quality 3D Assets: A library of photogrammetry-quality or expertly modeled and optimized 3D models of plants for a realistic experience. This is the most time-consuming and critical dependency.

Multimedia Content: Professional images, videos, and audio narration aligned with each plant entry.

Legal/Regulatory Clearance: Validation from Ministry of AYUSH on the accuracy of the medicinal information presented to ensure safety and adherence to traditional texts.

Mapping/Geographical Data: Accurate data for filtering plants based on native habitat and region.








