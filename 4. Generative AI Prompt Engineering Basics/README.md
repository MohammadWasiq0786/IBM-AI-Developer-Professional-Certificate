<center> <h1 style=color:red;> Generative AI: Prompt Engineering Basics </h1> </center>


<center> <h2> Module 1:  Concept of Prompt Engineering </h2> </center>

<center> <h3 style=color:orange;> Summary & Highlights </h3> </center>

Congratulations! You have completed this lesson. 

* A prompt is any input or a series of instructions you provide to a generative model to produce a desired output.
* These instructions help in directing the creativity of the model and assist it in producing relevant and logical responses. 
* The building blocks of a well-structured prompt include instruction, context, input data, and output indicators. 
* These elements help the model comprehend our necessities and generate relevant responses. 
* Prompt engineering is designing effective prompts to leverage the full capabilities of the generative AI models in producing optimal responses.
* Refining a prompt involves experimenting with various factors that could influence the output from the model.
* Prompt engineering helps optimize model efficiency, boost performance, understand model constraints, and enhance its security.
* Writing effective prompts is essential for supervising the style, tone, and content of output.
* Best practices for writing effective prompts can be implemented across four dimensions: clarity, context, precision, and role-play.
* Prompt engineering tools provide various features and functionalities to optimize prompts. 
* Some of these functionalities include suggestions for prompts, contextual understanding, iterative refinement, bias mitigation, domain-specific aid, and libraries of predefined prompts. 
* A few common tools and platforms for prompt engineering include IBM watsonx Prompt Lab, Spellbook, Dust, and PromptPerfect. 

<center> <h2> Module 2:  Techniques and Approaches for Writing Effective Prompts </h2> </center>

<center> <h3 style=color:orange;> Summary & Highlights </h3> </center>

* **Prompt Hacks**: Prompt hacks in generative AI refer to techniques or strategies that involve manipulating the prompts or inputs provided to a generative AI model, such as a large language model (LLM) or an image generation model, to produce desired or specific outputs. These hacks include carefully crafting the prompts to influence the model's behavior and generate outputs that align with the user's intentions. They improve the performance of LLMs by:
* **Improving the quality and accuracy of LLM outputs:** By carefully crafting the prompt, you can guide the LLM toward the desired output and reduce the likelihood of errors.
* **Enabling LLMs to perform new and innovative tasks:** By combining prompts with other inputs, such as images or code, you can enable LLMs to perform tasks that they would not be able to perform otherwise.
* **Making LLMs more accessible and user-friendly:** Using prompt hacks can make it easier for people to use LLMs easily and effectively.

* **Prompt hacks and text-generation**
Prompt hacks can be used with LLMs to generate more effective responses from text-generating generative AI models in the following ways:

* **Using special modifiers:** LLMs have special modifiers that can control the style, tone, and other properties of the generated output. For example, you might use the modifier "write in a humorous style" to generate a funny poem or story.

* **Providing context and examples:** The more context and examples you provide to the LLM, the better it will be able to understand what you want and generate the desired output. For example, if you wish the LLM to generate a code snippet for a specific task, you might provide it with a detailed description and some examples of similar code snippets.
* **Combining prompts with other inputs:** Prompts can be combined with other inputs, such as images or code, to generate more complex and informative outputs. For example, you might prompt an LLM to generate a description of an image while providing it with the image itself.

Here's an example of using prompt hacks with text-generating models. 

You need a poem about a cat. So, you use the following prompt:

Prompt: Write a poem about a cat.

Output:
```plaintext
A furry little creature,
With four paws and a tail,
It loves to chase mice,
And play with its ball.
```

Now, this is a fairly straightforward poem about a cat. However, you require a slightly innovative output. You can use prompt hacking to bring in more creativity or humor. For example, you could add the following modifier to the prompt:

Prompt: Write a poem about a cat in the style of a gangsta rapper.

Output:
```plaintext
Yo, I'm a cat, and I'm here to say,
I'm the coolest cat around today.
I got fur so soft and eyes so green,
And I'm the best hunter you've ever seen.
```

You now have a poem, about a cat, which is creative and funny!

Prompt hacks and image generation
Did you know you can use prompt hacking with LLMs to create images?

Directing image generation models through LLMs is an emerging method that is gaining popularity in artificial intelligence. This approach entails employing an LLM to guide an image generation model, like DALL-E 2 or Imagen, to produce more precise and lifelike images.

How exactly does this work?

You provide the LLM with a text description of the image you want and then use the LLM's output to guide the image generation model.

For example, suppose you want to generate an image of a cat sitting on a couch. You could provide the LLM with a text prompt like this:

Prompt: "A fluffy orange cat sitting on a red couch, looking at the camera."

The LLM would then generate a response like this:

Output:
```plaintext
"A fluffy orange cat is sitting on a red couch. It is looking directly at the camera. Its eyes are green, and its fur is soft and smooth."

You can then use this response to guide the image generation model to generate an image of a cat sitting on a couch such that it matches the description provided by the LLM.

Here's another example. Imagine you need a background image for the poem "Twinkle twinkle little star."
```

You can use a prompt hack here and ask the LLM to suggest the prompt for generating this image.

Prompt: Consider the poem "Twinkle twinkle little star." Can you create a text description of an image that represents this poem?

The following image depicts the response generated by ChatGPT using this prompt.

Output:
```plaintext
The prompt hack comes after this. 
```

Prompt: Can you suggest a prompt that will be helpful to generate a relevant image for description: "In the serene backdrop of a dark velvet sky, a single radiant star takes center stage. The star glistens with a soft silver glow, casting a gentle, shimmering light onto the tranquil night landscape. The surrounding darkness is dotted with more distant stars, creating a celestial tapestry that seems to stretch forever. The star in focus stands out like a diamond in the sky, a beacon of hope and wonder. It symbolizes the innocence and curiosity of childhood, reminding us of the simple joys of looking up at the night sky and dreaming."

Output: 


Now, if you need to use the same prompt for DALL-E, you can also use a prompt hack here!

Prompt: Can you rewrite the prompt for DALL-E?

Output:



Bingo!

You now have what you want. You can use these images for the poem the way you'd like. 

Prompt hacks and prompt engineering
Prompt hacking and prompt engineering are closely related fields, but they have some key differences.

Prompt hacking is the use of prompts to manipulate the output of an LLM in a way that is unexpected or unintended, whereas prompt engineering is the systematic design and development of prompts for LLMs


|   | **Prompt Hacks**| **Prompt Engineering** |
|---| --------------- | ---------------------- |
| **Purpose** | To manipulate the output of an LLM in unexpected or unintended ways| To improve the performance of an LLM on specific tasks. |
| **Approach** | Experimental and creative |Systematic and disciplined|
| **Application** | Generating humorous or creative outputs | Improving the performance of LLMs in machine translation, question answering, and other tasks |

It is important to note that the distinction between prompt hacking and prompt engineering is not always clear-cut. Some techniques can be used for both purposes. For example, using special modifiers to control the style and tone of the output to generate humorous or creative outputs. It can also be used to improve the performance of an LLM on a specific task, such as generating text in a specific style.

**Tips for powerful prompt hacking**
Here are some additional tips for prompt hacking:

    * Be creative, and don't be afraid to try new things
    * Be specific and clear in your instructions.
    * Use the LLM's documentation to learn more about its capabilities and limitations.
    * Experiment with different prompts and see what works best for you.

With some practice, you can use prompt hacking to generate high-quality and creative outputs from LLMs.

To conclude, prompt hacking is a powerful technique that can be used to get the most out of LLMs. However, it is a relatively new field, and there is no one-size-fits-all approach. The best way to learn how to hack prompts is to experiment and discover what works for you.