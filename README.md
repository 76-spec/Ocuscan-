# Ocuscan- Assistente per l’Immagine di Patologia o Ocuscan 

AI-Powered Eye Pathology Image Analysis Assistant

Project Overview

Assistente per l’Immagine di Patologia is an AI-powered educational assistant designed to support students studying Optics at upper-secondary school level and optical professionals in learning about visible ocular abnormalities.

The assistant allows users to upload photographs of the external eye and receive an educational analysis of visible anatomical features and possible ocular alterations.

By combining image understanding and conversational Artificial Intelligence, the project aims to connect theoretical knowledge with practical visual examples.

Important: This is an educational prototype. It does not provide medical diagnoses and does not replace an ophthalmological examination or professional assessment.

Project Presentation

Try the AI Assistant

Open the public chat https://dioptraai.app.n8n.cloud/webhook/911a35f7-c5c3-4269-a458-7d25873d156a/chat

Explanatory Video

Watch the project presentation video https://drive.google.com/file/d/1lgF-0r451DiQM3wGcsbkv49w9L5V2Xd2/view?usp=drivesdk

Explanatory Image

View the project infographic https://drive.google.com/file/d/1gTvrYbD3aFEgfxo04syVavWSxDv-z_De/view?usp=drivesdk

Main Features

The assistant can:

* Accept photographs of the external eye, conjunctiva, cornea, iris, pupil and eyelids.
* Describe objectively the visible characteristics of an uploaded image.
* Identify visual patterns potentially compatible with common ocular alterations.
* Explain the anatomical structures involved.
* Describe typical signs and symptoms associated with possible conditions.
* Compare alterations with similar visual appearances.
* Provide scientific explanations in accessible language.
* Ask additional questions when further context is useful.
* Support learning through practical image-based examples.

Ocular Alterations Covered

The educational scope includes examples such as:

* Conjunctival redness
* Corneal opacity
* Pterygium
* Pinguecula
* Stye (hordeolum)
* Chalazion
* Ptosis
* Other visible alterations of the anterior eye.

The assistant distinguishes observable features from possible interpretations and does not confirm a condition based only on an image.

Educational Response Structure

For each uploaded photograph, the assistant provides a structured response:

1. Image Description: Objective description of what is visible.
2. Anatomical Structure: Identification of the ocular structures involved.
3. Possible Alterations: Possible conditions compatible with the visible features.
4. Clinical Explanation: Educational explanation of their characteristics.
5. Differential Considerations: Comparison with other conditions that may look similar.
6. Educational Summary: The most important concepts students should remember.
7. Professional Assessment: Guidance on when an ophthalmological examination may be necessary.

Problems Addressed

For Optical Professionals

* Support in understanding and recognizing visible ocular alterations.
* Better knowledge of common abnormalities affecting the external eye.
* Educational support when identifying signs that may require referral to an ophthalmologist.
* A useful resource for reviewing ocular anatomy and common conditions.

For Optics Students

* Difficulty recognizing ocular alterations from photographs.
* Limited opportunities to connect theory with practical visual examples.
* Difficulty distinguishing between conditions with similar appearances.
* Need for clear explanations of ocular anatomy and pathology.
* Support in preparing for practical activities and future professional work.

Workflow Architecture

The project is developed using n8n and includes the following components:

1. Chat Trigger: Receives messages and image uploads from users.
2. AI Agent: Manages the conversation and coordinates the educational analysis.
3. OpenAI Chat Model: Processes the request and generates explanations.
4. Image Input and Analysis: Allows users to upload eye photographs for visual analysis through an image-capable model.
5. Response Generation: Organizes the results into a structured educational response.

The workflow connects the Chat Trigger, AI Agent and OpenAI Chat Model, with image input capability integrated into the analysis process.

Technologies Used

* n8n: Workflow automation and orchestration.
* OpenAI: Artificial Intelligence and image understanding.
* AI Agent: Conversational educational assistant.
* Chat Trigger: User interaction and image submission.

Ethics and Responsible AI

The assistant is designed exclusively for educational purposes.

* No definitive diagnosis: The system describes visible features and discusses possible interpretations without confirming diseases.
* No prescriptions: It does not recommend or prescribe medication or treatments.
* Professional assessment: AI-generated suggestions must not replace evaluation by a qualified healthcare professional.
* Urgent situations: Sudden vision loss, severe eye pain, chemical exposure and ocular trauma require urgent medical evaluation.
* Image limitations: Lighting, focus, resolution and viewing angle may affect the analysis.
* Privacy: Users must not upload identifiable patient information. Only educational images or images shared with appropriate consent should be used.
* Human responsibility: The information generated by the AI must always be interpreted critically.

Testing

The prototype can be evaluated using educational photographs representing different ocular structures and visible alterations.

Suggested test cases include:

* Normal external eye appearance.
* Conjunctival redness.
* Pterygium and pinguecula.
* Stye and chalazion.
* Ptosis.
* Possible corneal opacity.
* Poorly illuminated or blurred photographs.
* Images that do not clearly show the eye.
* Reported symptoms that may require urgent medical assessment.

Testing should evaluate the quality of image descriptions, clarity of explanations and ability to communicate limitations.

Project Objective

The objective of the Assistente per l’Immagine di Patologia is to demonstrate how Artificial Intelligence and image analysis can support education in Optics.

The project provides an interactive learning experience in which students can explore ocular images, understand visible alterations and strengthen their knowledge of ocular anatomy and pathology.

Observe. Understand. Learn. Artificial Intelligence in the service of optical education.
