"Who can it be, knockin' at my door? Go away, don't come round here no more"
<sup>Men At Work - Who Can It Be Now?</sup>

A *Use Case* is a <u>written description</u> of the user's <u>interaction</u> with your product in order to <u>achieve a certain goal</u>. For example:

"As a <u>productive user</u>, I can <u>switch workspaces</u> on my desktop."

Use Cases are used within the [[Chapter 1.1 - The Software Development Life Cycle (SDLC)#The **<u>Planning & Requirement Analysis</u>** Phase|Requirement Analysis]] and [[Chapter 1.1 - The Software Development Life Cycle (SDLC)#The **<u>Design</u>** Phase|Design]] phases of an SDLC.

## UML (Unified Modeling Language)

UMLs are used to design diagrams and visualise a project. The main type of UML we are concerned with is, of course, the Use Case diagram.

So, why use one? Well, they are great for communicating complex ideas with others, especially those who are <u>non-techincal.</u>

It is important to know that Use Case diagrams <u>do not</u> describe how exactly the ideas are implemented. They <u>describe</u> different types of <u>roles in a system</u> and how they <u>interact</u> with it.

![[Pasted image 20240904154436.png]]


Now, I'll break this diagram down into each element and explain them to you. 

- The big rectangle that covers the ovals is the <u>system boundary</u>.
	- This sets a <u>system's scope</u> to use cases.
	- System boundaries have <u>names at the top</u>.
	- Everything outside the boundary is considered <u>outside of the scope of the system.</u>

- The stickmen beside the rectangle are <u>actors</u>.
	- They are the <u>users of the system</u>.
	- Actors are named by <u>nouns</u>. Please give them <u>meaningful names</u> that clearly describe their role in relation to the system, like this. ![[Pasted image 20240904160759.png]]
	- Typically, users on the <u>left</u> side are the <u>primary users</u> while users on the <u>right</u> are <u>secondary users</u>.
		- **Primary users** are users that <u>initiate the use of the system</u>.
		- They are typically placed on the <u>left side</u> for easy highlighting. *However, if there are few primary actors, it is okay to place them on any side of the system boundary.*
		- **Secondary users** are users that <u>react to the use case</u>, <u>providing a service</u> but <u>not interacting with the system on their own</u>.
		- Typically placed on the <u>right side</u> of the boundary.

- The ovals themselves are <u>use cases</u>.
	- They <u>are a written description of</u> exactly what actions the user can use with the system while <u>interacting with it</u> to <u>accomplish a goal</u>.
	- Named by <u>verb</u>. Don't elaborate on each use case too much, but don't make it too short either.
	- When making these, think of the <u>user's end goal</u>.
	- It's a good idea to try list these in logical order.

- The lines between the elements are <u>associations</u>.
	- These show the <u>relationships between actors and use cases</u>.
	- Indicated which use case is available to which actor.
	- There are more complicated relationships that will be discussed next chapter.


So, how do you go about making one of these?

- Set the scope of the system (system boundary)
	- Identify users and their roles in the system (actor)
		- Create use cases (oval) for every goal an actor has
			- Structure the use cases (next chapter)
				- Prioritise, review and refine the use cases.

 ---
 

There are a few more complicated relationships when it comes to a UML. These are:

- Include
- Extend
- Generalisation of a use case
- Generalisation of an actor


#### Include

This one refers top use cases that are **required** by another use case to work. Try thinking of this one as a use case that *includes* another use case to function (because that's kinda exactly what it is).

For example, in order to play an online RPG, the player **must** create an account beforehand. In this case, the base use case would be something like "Play Online Game", and the included use case would be something like "Create Account".

![[Pasted image 20240904212858.png]]

Included use cases are typically placed on the <u>right side of the base use case</u>, as can be seen from the image above. Alongside that, they are to be <u>connected with a dashed arrow</u> pointing **towards** the <u>included use case</u>, with the **label "<\<include>>"**.


It is possible and valid to have multiple use cases including one same use case, or to have one use case linked to multiple included use cases.



#### Extend

As compared to the Include relationship, this one refers to use cases that are optional for the base use case to work. Think of it as, well, an extension of the base use case. It's there, but it isn't really *fundamental* for the thing to function.

For example, when playing on the online RPG, you are given the option to change your skin, but you can also go along without doing so. Here, the base use case is, still, to play the online RPG, but the extended use case is to change the user's skin.

![[Pasted image 20240904213924.png]]

This essentially has the same element rules as Include, just that this time the arrow is <u>pointing toward the base use case</u>. Of course, there is also the label change too.

---

#### Use Cases with Extension Points

Extension points are essentially a detailed version of relation between use ca- Huh? What? Wait, this *isn't* tested?

![[Pasted image 20240904214230.png]]



Would you look at that? Less work for me, I guess.

---

![[Pasted image 20240904214340.png]]

This picture more or less summarises the difference between these two. Look at it. Move on once you're done with it.

<br>
<br>
<br>
<br>
<br>
<br>
<br>

...You understand it? Great. Now, we can get to the generalisation of stuff.

---

### Generalisation of Use Cases and Actors

This one is pretty cool. This essentially bundles multiple use cases into one.

![[Pasted image 20240904214915.png]]


For you programmingpilled pythonmaxxers, you can kinda think of this as a function.

Just like how you can store multiple lines of code in a function for it to be called when you need it, you can store multiple use cases into one generalised use case for it to be used when you need it.

The <u>individual</u> use cases are called <u>children</u>, and the <u>generalised</u> use case made of children is called a <u>parent</u>.

We can also do the same thing to actors.
![[Pasted image 20240904215304.png]]

For actors, the children inherit properties and behaviour of its parent, but can also have other unique behaviours. I'd compare this to a Python class, but I'm not sure if I'd be correct.

For generalised stuff, we draw them with <u>hollow triangles</u> that <u>point to the parent</u>, with the <u>children beneath</u> them.


---
Mikhail