# Week 1

[Weekly Goals](#weekly-goals) | [Daily Goals](#daily-goals) | [Weekly Challenge](#weekly-challenge) | [Weekend Challenge](#weekend-challenge) | [Workshops](#workshops)



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
attr_asscessor/reader/writer
step 12 resources
- REFLECTION: Got better understanding on TDD process through the workshop. l

### Day 4
- GOAL: Practice TDD throght Birthdays project. Filling all the knowledge gaps
- REFLECTION:


## Weekly Challenge
**Boris-Bikes**


## Weekend Challenge
**Airport**
airport
add readme of boris


## Workshops

### Debugging Workshop

1. How will you validate that you progress towards the week 1 goals?
 -	Feedbacks from peers – reflection
 -	Working code 
 -	Airport challenge
 -	Screen recording
 -	Diagram of process
 -	Explain to someone
 -	Write an explaination

2. Bugs
-	Programme is not working as intended –Syntax error/ Runtime error (name error)/ Programme not terminating/ Unexpected results

3. Debugging
-	Understand the problem
-	Fix it (intentional)
-	Look, click on slaktries

### TDD Workshop

1. TDD
- Process of writing test to guide the codes that meets user needs
- Reason of using it is to help to break down the problem, build the project step by step
- Can serve as docs/ Acts as safty net

2. Steps of building up a project
- Define user needs
- Write user stories
- Domain Model
- Write a feature test (What is the beheviour I expect?)
- `rspec -fd` (gives a description of the actions the code do)

3. Things we need to use in spec file
- `expect` matchers
    - `.to eq`
    - `.to raise_error`
    - `.to output`
- `describe`
- `it`

4. Live Coding
**PiggyBank**
- Store money
- Discourge people from taking it out
- Destroy/take the money out
- Shaking it to check there is money inside
- PiggyBank object/ store method
- User Story: 
```
As a user. 
So I can save up money. 
I want to store money in a piggy bank.
```

**Feature Test**
```
piggy_bank = PiggyBank.new
piggy_bank.store(1)
=> "clink"
```
```
piggy_bank = PiggyBank.new
piggy_bank.store(1)
piggy_bank.destory
=> 1
```

**Spec File**
```
describe PiggyBank do
  descibe "#store" do
    it "should return 'clink' when I store 1 pound" do
    piggy_bank = PiggyBank.new
    expect(piggy_bank.store(1)).to eq ('clink')
  end
end
```
```
decribe "#destory" do
  it "should return 1 when I ha stored 1 pound" do
    #arrange
    piggy_bank = PiggyBank.new
    piggy_bank.store(1)
    #act + assert
    expect(piggy_bank.detrory).to eq (1)
  end
end
```


**Rb File**
```
class PiggyBank
  def store(amount)
    "clink" if amount > 0
  end
  
  def detory
  end
end
```

