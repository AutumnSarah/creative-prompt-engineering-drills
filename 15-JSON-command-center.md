# JSON Command Center 

**Challenge:** Write prompts that use JSON to give the model precise instructions that generate specific outputs. Paste your prompt into an LLM and observe if the output matches your expectations. 

JSON prompting is a technique that uses the JavaScript Object Notation (JSON) format to provide explicit, structured instructions to large language models (LLMs). Instead of relying on free-form natural language, JSON prompts use a system of key-value pairs, objects, and arrays to define the exact task, context, constraints, and desired output format. When you provide JSON in your prompt, you're giving the AI structured data to work with. This is powerful for:

* **Configuration:** Setting parameters for how the AI should behave  
* **Data Processing:** Giving the AI structured information to transform  
* **Templating:** Providing schemas for the AI to fill in  
* **Multi-step Instructions:** Breaking complex tasks into organized components

**Your Goal:** Create a JSON prompt for each of the following tasks that specifies:

* Request  
* Response style or format  
* Maximum length or word count (if applicable)  
* Required elements or information to include  
* Negative restrictions such as forbidden topics or words

**Example Task:**   
Write a JSON prompt to make the AI respond as a pirate captain describing a quest..

{

  “task”: “describe the pirate’s quest”

  "response\_style": "pirate\_captain",

  "max\_words": 50,

  "must\_include": \["treasure", "adventure"\],

  "forbidden\_words": \["modern", "technology"\]

}

## Round 1

**Task:** Write a JSON prompt to generate a 10 line poem about the weather. 

## Round 2

**Task:** Write a JSON prompt to write a product description for a new invisible magic wand. 

## Round 3

**Task:** Write a JSON prompt to convert this list of pirate artifacts into a table: Flintlock Pistol, Cannon, Ship's Bell, Spanish Coin, Treasure Chest, Indigo Dyed Silk, Captain’s Journal, Navigation Map, Barrel of Gunpowder, Silver Locket, Anchor, Sails

## Round 4

**Task:** Write a JSON prompt to plan a roadtrip itinerary to visit five U.S. landmarks. 

## Round 5

**Task:** Write a JSON prompt that asks the model to summarize an article. (Any article you choose)
