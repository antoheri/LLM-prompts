# \# LLM Prompting
Promt librairy to improve productivity with LLM like ChatGPT.

## How to create good prompts

### The 6 prompt components

When writing a new prompt, go down this check list : 

_Mandatory_
1. Task
2. Exemplar

_Important_

3. Context
4. Persona

_Nice to have_

5. Format
6. Tone

```
[persona] + [context] + [task] + [exemplar] + [format] + [tone]
```
This formula will give you a good output, wowerever, you don't need to use the six components. 

---

### 1. The task
Always start the task sentence with an action verb, ex: generate, give, write, analyze, etc. and clearly articulate what your end goal is.

It can be a simple task or a multi-task. Use a verb for each one of them. 

_`Analyze` the collected feedback, `summarize` the top 3 takeaways and `categorize` the rest._

### 2. The context
It can be quite difficult to define, here is three questions to refine your context : 

- What is the user's background ? 
- What does success look like ?
- What environment are they in ?

_`I'm a computer science student studying for a bachelor's degree.`  
`I have to pass my exam on big data in 2 weeks.`  
`I have very little time to revise.`  
Give me 3 points to prioritise to understand this subject._

The key is to give just enough information to constraint the endless possibilities.

### 3. Exemplar
Adding exemplars to the prompt drastically improves the quality of the output. 

_John Dohe, Athlete, Monaco  
Alice Reed, Computer scientist, New-York  
Megan Dahl, Driver, London  
Re-write this list using this structure: 
"My name is X, I work as a Y and I live in Z"  
`For example:   
My name is Carlos, I work as a Cook ans I live in Zurich.`_

### 4. Persona

Who the AI needs to be ? Who do you want to talk. Specify expert or profession for any domain. 

_`You are an expert in cybersecurity, with more than 10 years of experience, give me...`_

It also works with famous personalities, even non-real ones.

### 5. Format

Specify and visualize the exact format of the result.

_`Sort these feedbacks and display the results in a table with column headers: 'Feedback,' 'User,' 'Date'.`_

Formats examples :

- Emails
- Table
- Bullet points
- Code blocks
- Paragraphs
- Markdown

### 6. Tone
Specify the tone of the result : 
With enthusiasm, pessimisstic, formal, casual. 
