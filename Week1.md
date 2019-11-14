# Week 1

## Weekly Goals

1. Test-drive a simple program using objects and methods
2. Pair using the driver-navigator style
3. Follow an effective debugging process
4. Describe some basic OO principles like encapsulation, SRP

## Daily Goals
### Day 1
- GOAL: Debug errors using the knowledge from the workshop
- REFLECTION: Learned the pairing/debugging skills
> We did it well on our first pairing programming of the project, working on diagrams which outlined the structure of the project and brainstorming the ideas

### Day 2
- GOAL: Understand some basic ideas of TDD (Test Driven Development)/ Improve my knowledge of Domain Modelling, Feature Test and User Stories
- REFLECTION: Got lots of practice in reading error messages, debugging, RSpect
> We folloewd the steps, stopped and explained to each other the error messages, swiched deiver/navigator frequently
> Figured out the gaps during the pairing

### Day 3
- GOAL: Look at basic OO principles like encapsulation, SRP & Debugging and some Ruby methods
chars map
matchers of expect in spec file
- REFLECTION:

### Day 4
- GOAL: Practice TDD throght Birthdays project. Filling all the knowledge gaps
- REFLECTION:


## Weekly Challenge
**Boris-Bikes**


## Weekend Challenge
**Airport**

## Workshops

### Debugging Workshop

How will you validate that you progress towards the week 1 goals?
-	Feedbacks from peers – reflection
-	Working code 
-	Airport challenge
-	Screen recording
-	Diagram of process
-	Explain to someone
-	Write an explaination

Bugs
-	Programme is not working as intended –Syntax error/ Runtime error (name error)/ Programme not terminating/ Unexpected results

Debugging
-	Understand the problem
-	Fix it (intentional)
-	Look, click on slaktries

### TDD Workshop

TDD
- Process of writing test to guide the codes that meets user needs
- Reason of using it is to help to break down the problem, build the project step by step
- Can serve as docs/ Acts as safty net

Steps of building up a project
- Define user needs
- Write user stories
- Domain Model
- Write a feature test (What is the beheviour I expect?)

Live Coding
**PiggyBank**
- Store money
- Discourge people from taking it out
- Destroy/take the money out
- Shaking it to check there is money inside

-> Story: I am am user. I want to store money in a piggy bank.

-> PiggyBank object/ store method

[SPEC]
>describe PiggyBank do
> descibe "#store" do
> it "should return 'clink' when I store 1 pound" do
>  piggy_bank = PiggyBank.new
>  expect(piggy_bank.store(1)).to eq ('clink')
>  end
> end
>end

[RB]
>class PiggyBank
> def store(amount)
>  "clink"
> end
>end

Things we need to use in spec file
- expect -- matchers (.to eq/.to raise_error)
- describe
- it
