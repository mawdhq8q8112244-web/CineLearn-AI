Designing and developing an educational system based on generative artificial intelligence to transform academic content into visual narrative experiences, featuring adaptive educational assessment.


introduction

In recent years, the education sector has seen an increasing shift toward the integration of artificial intelligence (AI) technologies—specifically generative AI—for the creation, personalization, and delivery of educational content. The use of AI in education has evolved beyond merely answering questions or providing text-based assistance; it is now capable of generating text, images, audio, video, and multimedia educational content. This development has spurred a growing body of research focused on the creation of educational videos using generative AI, and the potential for these videos to serve as an alternative or a supplement to traditional instructional materials.
A recent review, published in *Frontiers in Computer Science* in 2026, analyzed 15 studies on the use of AI-generated educational videos in higher education. The review identified two primary production models: the first involves the complete generation of videos using AI technologies, while the second utilizes AI as a supporting tool in the video production process. The review also highlighted potential benefits—such as increased efficiency, scalability, personalization, content accessibility, and enhanced engagement and retention—while noting persistent challenges related to content quality, the nature of interaction, and the risks associated with employing AI in the educational process.
These developments coincide with a growing interest in personalized and adaptive learning, where AI systems can analyze a learner’s characteristics, performance, and behavior to tailor educational content to their specific needs. A systematic review published in 2025, which analyzed 142 peer-reviewed empirical studies on artificial intelligence (AI) technologies in adaptive education, demonstrated that machine learning, deep learning, and multimodal analytics can be employed to dynamically tailor educational content to individual learner profiles. However, issues concerning privacy, interpretability, and scalability remain significant challenges.
In this context, recent evidence has also emerged highlighting the importance of personalization in educational video. A 2026 field study involving 493 university students found that 88.4% of participants ranked a personalized video format as their top preference. Furthermore, students preferred AI-generated videos—when personalized for them—over pre-recorded videos featuring human instructors that lacked such personalization. These findings suggest that personalization plays a crucial role in how learners accept AI-generated educational content, even while students continue to value human presence, naturalness, and emotional expression.
This serves as the foundation for the system proposed in this study. The system does not view video merely as the ultimate objective of AI integration, nor is it limited to simply converting a PDF document or lecture transcript into a video. Instead, it proposes transforming academic content into an adaptive, narrative-driven visual learning experience. Knowledge can be presented in various formats—such as a short educational film, a specific scene, an episode within an interconnected series, or a standalone story—with the flexibility to select a narrative style tailored to the nature of the subject matter and the learner’s individual preferences. The experience can span multiple lectures, with each lecture serving as an episode in a single, overarching narrative; alternatively, each lecture could feature a distinct story with its own unique characters and events.
The storytelling approach proposed here is not intended to transform scientific information into mere entertainment, detached from the original subject matter. Rather, it uses narrative as a tool to re-contextualize scientific concepts within a visual framework that is easier to follow and comprehend. For instance, a scientific concept might be personified as a character, or the relationship between two concepts could be framed as an event—or a problem—that the characters must resolve, all while preserving the scientific integrity of the original content. The system can present this experience in various visual styles—such as a cinematic, realistic aesthetic, animation, or other formats—with the flexibility to switch styles between lectures based on the user’s preferences.
The process does not end with the creation and consumption of content; the proposed system includes an evaluation phase following the narrative experience. The system can generate a test based on the concepts covered in the story, then analyze the learner’s responses to identify which concepts have been mastered and which remain areas of weakness. Based on these results, the system—in more advanced iterations—can direct the learner to the relevant theoretical material for the concepts they struggled with, followed by a re-evaluation after the review. In this way, the application of artificial intelligence shifts from the simple production of static educational material to a comprehensive learning cycle that encompasses content creation, study, assessment, analysis, and adaptation.
Furthermore, the system can be utilized prior to a lecture, providing the student with a short introductory episode focused on the topic of the upcoming session. The purpose of this segment is not to replace the academic lecture, but rather to provide an initial overview of the concepts and terminology the student will encounter later, thereby helping to mentally prepare them for the course content. Following the lecture, a more detailed narrative experience—based on the material taught—can be developed, succeeded by assessment and analysis. In this way, the system can expand to support various stages of the learning journey, rather than serving merely as a tool for video production.



Research Problem


Despite significant advancements in generative artificial intelligence (AI) tools for education, many existing systems focus on a single function or a limited set of functions—such as generating video from text, providing interactive explanations, creating assessments, summarizing educational resources, or acting as a virtual tutor. While recent studies indicate that AI-generated educational videos have emerged as a distinct field of research, scientific evidence is still exploring how these videos are produced, utilized, and evaluated, as well as the challenges associated with them.
The problem addressed by this study lies in the gap between the generation of educational content and the design of a comprehensive learning experience built around that content. Producing an engaging educational video does not guarantee that the learner has grasped the concepts presented; similarly, creating a standalone assessment does not necessarily ensure that the test is precisely aligned with the content the student has viewed. Consequently, there is a need for a system that integrates original content, semantic analysis of concepts, narrative and visual generation, assessment, and the analysis of learner performance.
This challenge is further compounded by the diversity of academic content, particularly regarding the nature and sequencing of concepts. For some topics, a self-contained narrative may be most appropriate, whereas others may require a continuous storyline that spans multiple lectures. Furthermore, a learner might prefer a realistic, cinematic style for one subject, while favoring animation or a science-fiction aesthetic for another. Therefore, imposing a single video template across all educational materials fails to fully leverage the potential of generative AI. Accordingly, the research problem centers on how to design an educational system based on generative artificial intelligence that can analyze academic content and reorganize it into a flexible, visual, narrative-driven experience—while maintaining a clear connection to the original scholarly source—and subsequently assess the learner’s understanding, analyze their performance, and use these results to provide a more adaptive learning experience.


Study Objectives


This study aims to design an educational system that leverages generative artificial intelligence to transform academic content into diverse visual narrative experiences, moving beyond the limitations of traditional educational videos. The system analyzes educational texts and files to extract core concepts and their interrelationships, subsequently using them to craft an educational scenario—presented as a short film, a specific scene, an episode within an interconnected series, or a standalone story.
Furthermore, the study seeks to provide the flexibility to alter the visual and narrative style of the experience; for instance, lectures can be framed within genres such as science fiction, adventure, mystery, or action, all while ensuring that the scientific content remains the foundational element guiding the generative process.
The system also aims to support educational continuity by enabling the creation of a series of linked episodes—where each episode corresponds to a lecture or a segment of a course—while maintaining consistent characters, a cohesive narrative world, and established relationships. Alternatively, the system can be configured for standalone stories, where each lecture is presented as a distinct narrative experience.
Another key objective is to utilize the system in the pre-lecture phase to generate introductory content that helps students build foundational knowledge, and in the post-lecture phase to revisit and present concepts through a narrative lens, followed by experiential assessment and performance analysis.
Ultimately, this study seeks to integrate narrative-based learning, generative AI, multimodal learning, adaptive assessment, and learning analytics into a unified educational framework.


theoretical basis for the idea


The concept is based on the premise that learning does not occur solely through reading information; rather, it is influenced by how that information is presented, organized, and interconnected. Storytelling allows information to be placed within a context—incorporating characters, events, challenges, and relationships—which helps the learner follow a sequence of concepts, rather than treating them as a collection of isolated definitions.
In the proposed system, storytelling does not replace scientific content; instead, it serves as a representational layer built upon it. The original educational material remains the primary source, while generative artificial intelligence is used to reorganize it, transforming it into scenarios, scenes, dialogues, images, sounds, and videos.
This relationship becomes even more significant when the system is capable of generating multiple representations of the same content. A single concept can be introduced through a theoretical explanation, subsequently represented within a narrative, and finally used as the basis for assessing the learner. This process fosters connections between theoretical knowledge, visual representation, and evaluation.


Proposed System Model


The system begins with an educational resource—such as a PDF lecture, a presentation, text-based notes, instructor-provided content, or any other material supported by the system. This material undergoes a content analysis phase to extract key concepts, terminology, definitions, relationships, and the logical sequence of information.
Subsequently, the system creates a structured representation of the extracted knowledge. This ensures that the generation of the narrative is not merely the result of a generic prompt to a language model—such as "write a film about this topic"—but is instead grounded in the specific information extracted from the educational source. This approach minimizes the risk of the narrative straying from the academic material or incorporating information not present in the original source.
In the next stage, the system defines the format of the narrative experience. Users can choose from options such as a standalone film, an interconnected series, independent episodes, or short scenes. It is also possible to determine whether the narrative should continue from previous lectures or begin anew. In the case of an interconnected series, the system retains information regarding characters, events, and the narrative world, allowing new episodes to build upon those that came before.
For standalone narratives, each lecture can feature a unique world, set of characters, and style. This offers greater flexibility for the learner and enables the system to provide a distinct experience for each topic, rather than forcing all lectures into a single, uniform template.
Once the narrative structure is established, the system generates the educational script, scenes, dialogue, and visual descriptions. These elements can then be directed to appropriate models for the generation of images, video, or audio. The system can offer two primary modes of visual experience: a realistic or cinematic style, and an animated or non-realistic visual style. The project does not necessarily require training a foundational video model from scratch; instead, the prototype can leverage existing generative models or APIs. The research contribution, therefore, focuses on designing the instructional workflow, linking the generated content to the source material, managing narrative continuity, and developing an evaluation framework along with the analysis of its results.


Narrative flexibility as an element of the system

One of the most important characteristics of the proposed system is that it does not treat “film” as the only form of content. The length of the lecture or the nature of its topic may be appropriate for a short scene, while another topic may require an entire story. The series of concepts may be interconnected so that a series is more suitable than stand-alone stories.
This is why the system allows several forms of submission. The material can be a single movie, a series of sequential episodes, parts of a single story spanning several lectures, or different stories for each lecture. The narrative type can also be changed between episodes or lectures when appropriate to the content or learner preferences.
This change does not mean that scientific information changes. Change occurs in the method of acting, directing, and narrative context, while the concepts extracted from the source remain the reference that determines what the student must learn.
This concept represents an educational narrative flexibility that can be one of the distinctive elements of the proposed system, while scientifically confirming that the claim is not that these functions individually have not been used previously, but rather in an attempt to integrate them within a single learning journey linked to content, evaluation, and adaptation.


Using the system before and after the lecture


The system is not limited to the post-lecture phase. It can also serve as a preparatory tool, providing students with a short episode or introductory story that outlines key concepts—without, however, acting as a complete substitute for formal academic instruction.
Following the lecture, the system can utilize the taught material to craft a more detailed narrative experience, transforming abstract concepts into events, characters, and situations. Once the content has been engaged with, the student moves on to the assessment phase.
In this way, the learning journey is structured around three interconnected stages: preparation, learning through a narrative experience, and post-learning assessment and analysis.

Assessment and Analysis of Learner Performance

Assessment is a fundamental component of the proposed system, as its success should not be measured solely by video quality or the engaging nature of the narrative. Once an episode or film concludes, the system can generate questions based on the concepts covered and subsequently analyze the learner’s responses.
If a student repeatedly struggles with a specific concept, the system can flag it as an area requiring review. In a more advanced version, the system could use this insight to provide additional theoretical explanations before re-testing the student.
Consequently, the system’s role does not end when the video concludes; rather, the assessment results are transformed into data that informs the next stage of learning. This creates an integrated cycle that links content generation, assessment, learning analytics, and adaptation.
This approach aligns with broader research trends in adaptive education, where recent reviews indicate that artificial intelligence systems can leverage learner data to tailor educational content in a more personalized and dynamic manner.


Customization

Personalization in the proposed system is not limited to adjusting the difficulty level of questions; it can also extend to the way content is presented. For instance, one learner might prefer a cinematic, realistic experience, while another might favor animation. Similarly, some learners may prefer a continuous, overarching narrative, whereas others might opt ​​for independent stories tailored to each specific topic.
This type of personalization enables the creation of a unique learning experience for each individual, all while ensuring that the same educational objectives are met. A field study published in *Scientific Reports* in 2026 underscores the importance of personalization in educational videos; it found that 88.4% of participating students ranked personalized videos as their top preference. Furthermore, when comparing the source of the content alone, there was a general preference for material featuring human-recorded elements.
Consequently, the system does not posit that artificial intelligence should replace the teacher; rather, it serves as a tool that expands the educational system's capacity to deliver diverse, personalized content.

Ethical Guidelines and Safety


Since the proposed system relies on technologies for generating text, images, and video, a safety and content-control mechanism is an integral part of its design—not merely an optional, secondary feature.
To this end, the system incorporates a verification layer that screens requests and content prior to the generation phase. This layer identifies content that the system is prohibited from depicting or generating visually. For instance, in the case of requests to create visual representations of prophets, messengers, or sacred religious figures, the system blocks direct visual generation. Instead, it offers an educational, non-depictive alternative—such as a textual explanation, a narrative account, or the use of symbols, settings, and events that do not involve the visual portrayal of the protected figure.
This does not preclude the system from addressing religious topics in general; rather, the restriction specifically targets the visual depiction of figures belonging to protected categories. This policy may be further developed to accommodate various usage patterns—for example, by including a dedicated mode for children that enforces stricter safeguards regarding visual and linguistic content, as well as topics deemed age-inappropriate.
Furthermore, the safety layer can be extended to restrict or block other forms of unsuitable content, including non-educational depictions of violence, sexually explicit material, and content deemed inappropriate for children. It also encompasses controls regarding the use of images of real individuals or the impersonation of their identities without authorization.
This layer reflects a fundamental design principle: the fact that an artificial intelligence system is capable of generating certain content does not imply that such content should be permitted.


Data and the Problem of System Training

A key aspect of the project is identifying the data source upon which the system will rely. The proposed system does not necessarily require the creation of a massive dataset—such as thousands of films or scripts—to train a video model from scratch. Instead, the primary source of educational data consists of content provided by users or instructors, including lecture files, presentations, notes, texts, and other educational materials.
The system utilizes this data to extract the necessary knowledge and concepts, subsequently employing existing generative AI models to produce scripts, scenes, and visual content. In this respect, the project differs from one focused on training a new foundational model for video generation.
As for system evaluation data, this may comprise a curated, limited set of lectures, educational topics, and assessments, alongside data on student performance during initial trials. Such data can be used to evaluate the system’s ability to maintain the integrity of scientific information, the quality of the narrative experience, the extent of student comprehension, and the accuracy of the generated assessments.
Should future phases necessitate the training of a specialized model or the fine-tuning of an existing one, this could be addressed as a subsequent research stage; it is not a prerequisite for demonstrating the feasibility of building the initial prototype.


Related Systems and Platforms


There is currently a range of tools that address certain aspects of the proposed system—whether in the production of educational videos, the comprehension of source materials, personalization, or assessment. From a scholarly perspective, it is important to acknowledge these existing systems rather than claiming that no similar solutions exist.
Some platforms offer services that convert content into educational videos using virtual avatars or AI-generated voices, while others focus on analyzing lecture materials to provide explanations and quizzes. There are also systems dedicated to interactive learning or course development.
Furthermore, several Arabic-language platforms have emerged in the field of AI-supported education; some facilitate video generation, interaction with educational materials, the creation of quizzes, or the development of educational narratives. Consequently, the value of the proposed project should not be predicated on the notion that "no Arabic tools exist." Instead, it should be based on an analysis of what these existing tools offer, identifying the specific niche where the proposed system can provide added value.
The focus of this project lies in integrating flexible educational storytelling, continuity between episodes, the ability to adapt narrative styles, visual generation, post-viewing assessment, performance analysis, educational personalization, and safety controls—all within a single, cohesive learning journey.


Research gap

A review of existing literature and systems reveals that generative artificial intelligence is now capable of producing educational videos, and that personalization has become an active area of ​​research. Furthermore, recent studies have begun to evaluate the impact of AI-generated videos on learning outcomes and student preferences.
However, the proposed system is motivated by the observation that these components often appear in isolated solutions or disparate functions—with some tools focusing on video generation, others on analyzing source material, facilitating interactive instruction, or handling assessments and personalization.
Consequently, this project addresses a gap by designing an integrated educational workflow that begins with academic material and concludes with data on student learning, ensuring that the generation process is not decoupled from the assessment process.
The proposed system is further distinguished by its treatment of narrative as a flexible educational structure rather than a static visual template. A single body of content can be presented in various formats—such as a standalone film, a serialized series, or individual episodes—with the ability to shift narrative genres across different lectures, all while maintaining the scientific content as the primary, authoritative reference.


Conceptual comparison between existing systems and the proposed project


| Criterion | Tools for Comprehending Educational Resources | Educational Video Creation Tools | Interactive and Adaptive Learning Tools | Proposed Project |
| :--- | :--- | :--- | :--- | :--- |
| **Starting Point** | Educational files and resources | Text, script, or presentation | Educational topic or content | A full lecture or academic course material |
| **Delivery Method** | Explanation, summarization, and questions | Video, characters, and audio | Interactive lesson and assessment | Educational visual narrative experience |
| **Narrative Structure** | Limited | Script-based | Not a primary focus | Film, scene, interconnected series, or standalone story |
| **Continuity Between Lectures** | Limited | Possible, depending on the tool | Varies by system | Designed to support interconnected episodes |
| **Variation in Narrative Genre** | Limited | Depends on generative capabilities | Not a core function | Part of the experience design |
| **Visual Style** | Tool-dependent | Generated video or virtual characters | Often not central | Realistic/cinematic or animated |
| **Post-Viewing Assessment** | May be separate | Not always part of the workflow | Available in some systems | An essential part of the learning cycle |
| **Analysis of Weak Points** | Limited or separate | Limited | Present in adaptive systems | Directly linked to the concepts learned |
| **Review and Retesting** | Not always interconnected | Not fundamental | Possible | Part of the proposed adaptive path |
| **Safety and Control** | System-dependent | System-dependent | System-dependent | A dedicated layer for controlling generation |

The table illustrates that the fundamental difference does not lie in the proposed system inventing a new video-generation technique, but rather in how it integrates multiple techniques into a single learning architecture.


innovative aspect of the project

The proposed innovation is best understood as an advancement in system design and functional integration, rather than the creation of a new foundational artificial intelligence model. The system does not aim to compete with global models by training a new generative video model; instead, it establishes an intelligent pedagogical layer that leverages existing generative models, directing them toward specific learning objectives.
A key feature is the concept of "flexible educational storytelling," which allows a lecture to be transformed into a standalone film, an episode within a multi-lecture educational series, or an independent narrative—with the ability to adapt the storytelling style and visual genre to suit different subjects.
A second aspect involves linking the narrative experience to assessment; the system’s function does not conclude with the generation of a video—it utilizes tests and learner performance data to identify concepts that require further review.
A third aspect is the system’s versatility: it can be employed both as a preparatory tool before a lecture and as a learning and assessment resource afterward, thereby supporting multiple stages of the educational journey.
A fourth aspect is the inclusion of a safety and ethics layer that governs the types of content the system can generate. This includes strict prohibitions—such as preventing the creation of visual representations of prophets, messengers, or sacred religious figures—while providing non-figurative alternatives whenever necessary.


Scope of Implementation in the Graduation Project

Although the full scope of the system is extensive, the graduation project can begin with a limited prototype that demonstrates the core concept. This prototype could start with specific educational materials, extract key concepts, generate a short scenario, produce a limited number of scenes, and finally assemble them into a brief video experience.
The prototype could focus on a short educational segment rather than attempting to produce a full-length cinematic film. It could also implement either a realistic or an animated style—depending on the capabilities of the available models—by utilizing the APIs of existing generative models, rather than training a video model from scratch.
Subsequently, features such as AI-generated testing, analysis of results, and the mapping of errors back to specific educational concepts could be added. More complex elements—such as long-term continuity across numerous segments, advanced personalization, in-depth understanding of learner preferences, a dedicated mode for children, expanded safety controls, and the generation of longer-form cinematic content—can be addressed as future development phases.
Distinguishing between the initial prototype and the long-term vision is essential to ensure the project remains feasible as a graduation project, while still maintaining a scalable research vision.


Scientific and Practical Significance

The scientific significance of this project stems from the intersection of several contemporary research fields, including generative artificial intelligence, multimodal learning, narrative-based learning, adaptive learning, learning analytics, and AI-generated assessment. Furthermore, there is a growing research interest in AI-generated educational videos; recent studies are exploring not only the feasibility of producing such content but also how it is utilized and its subsequent impact on the learner's experience.
From a practical perspective, the project addresses a common challenge in higher education: some students struggle to engage with lengthy theoretical lectures when presented solely through text, slides, or traditional instructional formats. The proposed system offers an additional representation of the course material, helping to make concepts clearer and more coherent—all while preserving the original academic source material and the instructor's role.
Additionally, the system enables instructors to utilize the same content in various ways, while allowing students to select the presentation format that best suits their individual needs—a feature that aligns with the broader trend toward personalization in AI-supported education.


Conclusion


This study proposes the design of an educational system based on generative artificial intelligence. Rather than merely converting lectures into videos, the system aims to construct an integrated narrative and visual learning experience—beginning with academic content and concluding with the assessment of student learning and the analysis of their performance.
The proposed system is characterized by the flexibility of its narrative format; a lecture can be presented as a standalone film, a short scene, an episode in a cohesive series, or an independent story. Furthermore, the narrative genre and visual style can be adapted for each lecture, depending on the nature of the content and the learner's preferences. This experience can be utilized prior to a lecture as an introduction, following it as a means to reenact and reinforce concepts, and during the assessment phase to identify areas of weakness.
The primary value of this project does not lie in developing a new model for video generation, but rather in designing an educational framework that bridges content comprehension, narrative generation, multimodal synthesis, assessment, performance analysis, personalization, and ethical integrity. Moreover, the proposed system does not posit that artificial intelligence should replace the instructor; instead, it aims to provide an additional tool that can be used to expand methods of content delivery and tailor the educational experience.
Recent research indicates that AI-generated educational videos have emerged as a significant field of study, with personalization serving as a key factor in how learners perceive such content. Meanwhile, research on adaptive learning underscores the importance of leveraging learner data to refine and customize the educational experience. Accordingly, the proposed system represents a research direction that integrates the capabilities of generative artificial intelligence with the principles of instructional design. It holds the potential for future development into an adaptive, narrative-based learning environment capable of generating diverse educational experiences, monitoring learner performance, and tailoring content to individual needs—all while maintaining content integrity and adhering to ethical standards.



References



1.	Hai, T. T., Mai, D. T. T., & Hanh, N. V. (2026). A rapid review of using AI-generated instructional videos in higher education. Frontiers in Computer Science, 7, 1721093. 
2.	Tomlinson, B., Black, R. W., Patterson, D. J., van der Hoek, A., Ferguson, J., & Bietz, M. J. (2026). Students prefer personalized, AI-generated educational videos over non-personalized, human-recorded videos. Scientific Reports, 16, 21804. 
3.	Hariyanto, Kristianingsih, F. X. D., & Maharani, R. (2025). Artificial intelligence in adaptive education: a systematic review of techniques for personalized learning. Discover Education, 4, 458. 


