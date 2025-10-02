# SolutionPlan_Template

# 1. Your Team at a Glance

## Team Name / Tagline  
PortoMotive / "Creating innovative automative solutions to save your life ;)"

## Team Members  
|      Name      | GitHub Handle |         Role(s)        |
|----------------|---------------|------------------------|
|  Bruno Miguel  |    Bruno0798  |   sof.developer        |
|  Rui Almeida   |     Rmsa42    |   sof.developer        |
|  Miguel Biltes |     Biltes    |   sof.developer        |
|   João Silva   |     jpjpcs    |   sof.developer        |
|Bernardo Esteves|    berestv    |   sof.developer        |

## Challenge  
SDV_LAB

## Core Idea  
*What is your rough solution idea?*

#### Main Idea
- Our main idea is to prevent rear collision accidents or in case of having a rear collision save lifes.
- We will implement an adaptive Rear Collision Evasion System (RCES) called BALS (Backward Automotive LifeSaving System).

#### The Problem
In traffic jams, the risk of rear-end collisions is high. Most current systems only prepare the occupants (seatbelt tensioning, headrest adjustment, hazard lights). There is no active technology to steer the vehicle and avoid or mitigate impact.

#### Our Solution
BALS (Backward Automotive LifeSaving System) - RCES (Rear Collision Evasion System)

- BALS will be the Intelligent detection system that will detect rapidly approaching vehicles from the rear (cameras, radar, lidar), and prevent human death.
- Real-time assessment of lateral and forward space (using LIDAR).
- Automatic micro-evasive maneuvers to the left/right (when safe) to reduce or avoid impact (when there´s no choice left)
- Integration with V2V (Vehicle-to-Vehicle Communication) systems: surrounding vehicles collaborate to create space for the evasive maneuver.

#### How it works
If there are vehicles in front of the car, the system will attempt to steer the car into an adjacent lane (either to the right or left), depending on whether the car is currently in the leftmost or rightmost lane, and only if a lane is available for the maneuver.
If no adjacent lane is available, the car will prepare for the collision by unlocking the brakes (of our car and the other cars) and attempting to distribute the force of the impact across all involved vehicles, minimizing the damage.

#### Benefits
- Enhanced safety in traffic jams and high-speed roads.
- Real innovation: moving from passive to active rear collision protection.
- Potential for patent and competitive differentiation.
- Scalable for future autonomous vehicles and cooperative driving systems.

### Tagline:
"If you can’t avoid the accident, avoid or reduce the impact and save lifes."

*Sketch something that helps understand e.g. mermaid chart*

![alt text](https://quickshare.samsungcloud.com/x7dfCe5Ebsjw)

---

# 2. How Do You Work

## Development Process  
*Brief overview of your development process.*

- We will try to work following an agile-inspired workflow, breaking down the project into small tasks and iterating quickly. 
- Each member is assigned specific responsibilities, and we hold regular check-ins to review progress and adjust priorities.

### Planning & Tracking  
*How do you plan and track progress?*

- We use GitHub Projects to organize tasks, set milestones, and track issues. 
- Progress is reviewed in daily stand-ups and updated in our project board.
- Since we are working with github, we thought to use github tools (tools such as creating several branches, PR (pull request), branch integration, and projects and issues).
- So we thought to, first of all:
. 1)create a project;
. 2)have a development branch;
. 3)a main branch and ;
. 4)additional branches each per feature.
- Basically, we are using a methodologie of developing a feature (so each feature has is own branch), developing the feature using only that branch (including testing, etc) and after developing it, make a PR (pull request) to the developing branch. 
- The developer that is working in that (feature) branch only submmits the entire branch to the PR after finishing the feature. During the job, he only uses the (feature branch) to develop it´s work. 
- We also use an addictional secure measure: After integrating a feature in the developing branch, we (the developer that is making the tester role) clone that branch and check if everything it´s ok before passing it to the Main Branch (the most stable one).
- Meanwhile, documentation explaining what will we do, what are the technologies that we´re using, the goal and how we are going to achieve it, it´s shared on the github shared folder.

### Quality Assurance  
*How do you ensure quality (e.g., testing, documentation, code reviews)?*
We only have time to make:
1) Peer code reviews for all pull requests;
2) have clear and updated documentation;
3) continuous integration: the methodologie that we described above also allow us to make continuous integration to run tests on every (feature) branch before merging it with development branch. Cloning development branch and testing it also allow us to add an addictional measuse secure. 

We didn´t have time to create automated testing for any feature.

## Communication  
*How does your team communicate?*
Our team communicates using Slack (preferably) and WhatsApp for quick updates and discussions.

## Decision Making  
*How are decisions made in your team?*
- After an initial brainstorming, we analyse and measure which are the good ideas. 
- After that initial phase, we select some of them (the ones that we think that could be implemented - and in the timeline that we have), and we vote. 
- So, decisions are made collaboratively during team meetings and we discuss options, consider feedback from all members, and aim for consensus.
Basically, our decisions are made in a democratic way (like it should be).
