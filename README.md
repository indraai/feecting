# feecting

Welcome to the #feecting language. The #feecting language is a meta-programming language similar to YAML or Markdown that enables Humans and Agents in the Indra Quantum Computing Environment to share a common interaction language.

Both Humans and Agents are able to write #feecting scripts that can be shared in the community or among friends. These scrips allow the system to send commands, retrieve data, load documents, or call any Deva Agent that is availaable to return the call.

Using #feecting scripts various interfaces and data representations can be made of data elements from Twitter, Youtube, Databases, JSON APIs, and any other service provided. These scripts can then be used to produce live reports that can be analyzed by both Humans and Agents alike.

## Basics

The first basic of a #feecting script is the container item. Where *ITEM* is the name of your container. This allows a developer to separate their scripts into containers or individual parts that can be used in other places, as you will learn later.

```
::BEGIN:*ITEM*

::END:*ITEM*

// example: Most #feecting documents begin with a MAIN container.
::BEGIN:MAIN
# Title

p:Inside here you can include #feecting script to build a component.

talk:#twitter timeline quinnmichaels
::END:MAIN
```

In the example above you can see a main container with a `Title` and a paragraph `p:`. After that you can see the `talk:#twitter ...` command. This talk command tells the script to talk to the #twitter deva and return the specificed information to the container item.

From this point we can get far more complext in writing our scripts with items like variables, logic sets, looping, buttons, menus, and countless other features that the #Feecting language enables in the Indra Quantum Computing Environment.


[Github Repo](https://github.com/indraai/feecting)  
[Back to indra.ai](https://indra.ai)  
&copy;2022 Quinn Michaels; All Rights Reserved.
