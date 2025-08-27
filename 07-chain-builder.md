# The Chain Builder 

**Challenge:** Start with a basic question and rewrite it into a multi-hop chain to require 3-4 information hops. Multi-chain hops require the LLM to connect different pieces of information in a chain of reasoning using logic in which the output of one step becomes the input of the next. This exercise builds the skill of designing prompts that require genuine reasoning and interconnected thinking rather than simple fact retrieval. 

Transform each starter question into a multi-hop prompt. Aim for chains like:

* Basic fact → Historical event → Person involved → Their birthplace  
* Invention → Inventor → Their nationality → That country's current leader

Test your transformed prompt in an LLM and evaluate the response. Did the LLM get the correct answer? If the LLM explained its logic, did it use sound logic and accurate information to reach its final answer? 

### **Sample Transformation:**

**Before:** "What is the capital of France?"   
**After:** "In which city would you find the museum that houses the painting stolen from the Louvre in 1911 and recovered in 1913?"

| Strong Multi-Hop Prompts: | Weak Multi-Hop Prompts: |
| :---- | :---- |
| ✅ Each step requires the previous answer ✅ Information comes from different knowledge domains ✅ Chain length is 3-5 hops  ✅ Final answer is specific and verifiable ✅ No shortcuts or obvious direct paths | ❌ Steps can be answered independently ❌ All information from same domain ❌ Too short (2 hops) or too long (6+ hops) ❌ Vague or subjective final answer ❌ Multiple valid shortcuts exist |

### Tips for Success

1. **Test your chains manually first** \- Can you follow the logic?  
2. **Mix knowledge domains** \- For example, History \+ Science \+ Pop Culture \= strong chains  
3. **Use specific, verifiable endpoints** \- Dates, numbers, and names work best. You should be able to find quality sources to support the facts.   
4. **Avoid common knowledge shortcuts** \- Don't let the LLM skip steps  
5. **Start with 3-hop chains** \- Build complexity gradually  
6. **Document successful patterns** \- Reuse effective chain structures  
   

## Round 1 (Easy)

1. "What is the capital of Japan?"  
2. "Who painted the Mona Lisa?"  
3. "What year was the iPhone first released?"  
4. "Who wrote Harry Potter?"  
5. "What is the largest ocean?"  
6. "Who was the first person on the moon?"  
7. "What is the tallest mountain?"  
8. "Who founded Microsoft?"  
9. "What is the fastest land animal?"  
10. "When did the Berlin Wall fall?"

## Round 2 (intermediate)

1. "What is the chemical symbol for gold?"  
2. "Who invented the lightbulb?"  
3. "What is the smallest country in the world?"  
4. "Who directed Jaws?"  
5. "What is the most spoken language?"  
6. "When was the Declaration of Independence signed?"  
7. "Who composed The Four Seasons?"  
8. "What is the hardest natural substance?"  
9. "Who was the first U.S. President?"  
10. "What is the longest river in the world?"

## Round 3 (Difficult)

1. "What is E=mc²?"  
2. "Who discovered penicillin?"  
3. "Who composed The Magic Flute?"  
4. "Who wrote 1984?"  
5. "What is DNA?"  
6. "When did World War I begin?"  
7. "Who invented the printing press?"  
8. "What is the speed of light?"  
9. "Who painted Starry Night?"  
10. "Who created the periodic table?"
