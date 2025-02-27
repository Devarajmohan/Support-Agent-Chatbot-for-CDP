# Assignment 2: Building a Support Agent Chatbot for CDP

## Objective
Develop a chatbot that can answer "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot should extract relevant information from the official documentation of these CDPs to guide users on how to perform tasks or achieve specific outcomes within each platform.

## Data Sources
- [Segment Documentation](https://segment.com/docs/?ref=nav)
- [mParticle Documentation](https://docs.mparticle.com/)
- [Lytics Documentation](https://docs.lytics.com/)
- [Zeotap Documentation](https://docs.zeotap.com/home/en-us/)

## Core Functionalities
1. **Answer "How-to" Questions**
    - The chatbot should understand and respond to user questions about how to perform specific tasks or use features within each CDP.
    - Example questions:
      - "How do I set up a new source in Segment?"
      - "How can I create a user profile in mParticle?"
      - "How do I build an audience segment in Lytics?"
      - "How can I integrate my data with Zeotap?"

2. **Extract Information from Documentation**
    - The chatbot should retrieve relevant information from the provided documentation to answer user questions.
    - It should navigate through the documentation, identify relevant sections, and extract the necessary instructions or steps.

3. **Handle Variations in Questions**
    - Handle size variations, e.g., extremely long questions should not break it down.
    - Handle questions irrelevant to CDP, e.g., "Which movie is getting released this week?"

## Bonus Features
- **Cross-CDP Comparisons**
  - The chatbot can answer questions about the differences in approaches or functionalities between the four CDPs.
  - Example question: "How does Segment's audience creation process compare to Lytics'?"

- **Advanced "How-to" Questions**
  - The chatbot can handle more complex or platform-specific "how-to" questions.
  - It can provide guidance on advanced configurations, integrations, or use cases.

## Evaluation Criteria
- Accuracy and completeness of assignment.
- Code quality and build.
- Handling of variations in question phrasing and terminology.
- Implementation of bonus features (cross-CDP comparisons, advanced questions).
- Overall user experience and chatbot interaction.

## Additional Notes
- You can use any natural language processing (NLP) libraries or frameworks to build the chatbot. Instead of NLP, you can also use a simple document indexer.
- You can choose to implement the chatbot as a web application using any tool.
- The focus of this assignment is software engineering and not model building.