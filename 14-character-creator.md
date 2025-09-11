# Character Creator

**Challenge:** Write a prompt that gets the LLM to generate a JSON profile for a fictional character that includes the specified information for each. Paste your prompt into an LLM and observe the JSON structure created. 

### Understanding JSON:

JSON (JavaScript Object Notation) is a lightweight data format that uses:

* **Objects:** {"key": "value"} \- curly braces with key-value pairs  
* **Arrays:** \["item1", "item2"\] \- list of comma-separated values inside square brackets  
* **Data types:** strings, numbers, booleans, null, nested objects/arrays

**Example Prompt:** Create a JSON structured object for the following character profile with only the following information: Alex Chen, age 28, Space veterinarian, from Mars Colony Beta, no super powers, likes collecting cards and skateboarding

**Example Structure:**   
{  
  "name": "Alex Chen",  
  "age": 28,  
  "occupation": "Space veterinarian",  
  "origin": "Mars Colony Beta",  
  "superPowers": null,  
  "hobbies": \[  
    "collecting cards",  
    "skateboarding"  
  \]  
}

## Round 1

**The Time-Displaced Professional:** A character from a different era trying to adapt to modern life \- like a medieval blacksmith working as a modern metalworker, or a 1920s jazz musician navigating today's music industry.

**JSON should Include:** name, birthday (including the year), today's date, occupation, interest or hobbies  

## Round 2

**The Corporate Anomaly:** A fantastical creature working in a mundane office job \- like a dragon who's an insurance adjuster, a vampire working in IT support, or a fairy employed as a wedding planner.

**JSON should Include:** name, city of residence, occupation, company,  skills/qualifications

## Round 3

**The Overqualified Underachiever**: Someone with impressive credentials working in a surprisingly simple job by choice \- like a PhD in astrophysics who drives an ice cream truck, or a former Fortune 500 CEO who now works at a local bookstore.

**JSON should include**: name, highest education, current job, previous achievements, daily responsibilities

## Round 4

**The Reformed Villain**: A former fantasy bad guy trying to find honest work \- like an ex-evil wizard working as a children's birthday party entertainer, or a retired troll who became a bridge safety inspector.

**JSON should include**: name, former evil role, new career, community acceptance level, and any other details you want to add

## Round 5 

**The Magical Mishap Victim**: Someone who got cursed or enchanted and now has to navigate life with bizarre magical side effects \- like a person who sneezes glitter clouds, or someone whose shadow runs away when they're embarrassed.

**JSON should include**: name, profession, magical affliction, how it happened, coping strategies or treatment, and any other details you want to add
