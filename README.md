# Inspiration
Our group felt that language learning experience only in a classroom did not give a student full immersion into the language and culture. A much more natural way of language acquisition was the experience of having a conversation with a real native speaker. To try to bridge the gap without creating an intimidating environment, we wanted to help people speak with a new language while being able to express their thoughts in their own tongue.

Linkguist, the bilingual online link for life-long linguists and language lovers alike.

# What it does
Linkguist creates a chat between two speakers of different languages, and shows both the original message and a translated message. By learning through context, a learner can better associate the two languages and grasp confusing concepts such as grammar, usage, and colloquialisms easier. Native speakers don't learn grammar rules, and we're leveraging Watson's ability to translate these colloquialisms into other's native languages.

Users go to the homepage and select between being an English speaker and a Spanish speaker. They then are put in a chat with a person that speaks the opposite language. They can start a conversation with the person speaking in their native languages, and translations are also displayed.

# How we built it
Our app was built with the inclusion of two essential APIs: Moxtra and IBM Watson's Translation built on Bluemix. Using a node.js server, we created a chat box through Moxtra. After catching outgoing messages and pushing them through the translation service, we sent both the original and the translated text. This enabled the user to have a seamless chat service in two languages.

# Challenges we ran into
No one on our team had previously implemented an API into a project, so getting Moxtra to work initially, even unextended, was a difficult task. There were many technical difficulties involving IBM Bluemix being under maintenance, preventing pushing of files from local systems to my butt. We wanted to have a very appealing splash page to welcome the user, and creating the front end design proved much more difficult than expected, especially involving image manipulation.

# Accomplishments that we're proud of
We not only managed to implement both API's successfully, but we have them working in tandem and integrated Watson's translation with our own modifications on Moxtra's chat service. The feeling of success when we were actually able to see the messages translated in front of us was very rewarding. Additionally, we're proud of our beautiful webpage design, and catching branding.

# What we learned
Coming in, none of us had leveraged an API, let alone linked them in series after modifying one of them. All of us are just freshmen, and together, we learned essential backend, networking, frontend and API development concepts that we can definitely use in the future.

# What's next for Linkguist
Currently, Linkguist is a two language service. We want to be able to expand it to a multi-language, multi-platform tool that people can use on any device, and anywhere in the world. Additionally, written word is only half a language. Combining the chat service with Moxtra's Video Chat API, and Watson's Speech-to-Text abilities, we can continue to assist students in their love for languages.
