# IDEA DETAILS:

My proposal is adding === as a way to shorten: variable = variable.lower() to variable === .lower(), this is similar to += but for methods.

Should this work for potentially all methods?

Yes It is best to have this work for all methods, this should also work for multiple methods and with arguments.

Here is a code example:

Without proposal:

username = "  Davidson  "

username = username.strip()
username = username.lower()
username = username.replace("l", "1")

print(username)

With proposal:

username = "  Davidson  "

username === .strip()
username === .lower()
username === .replace("l", "1")

print(username)

Notice how both examples produce identical results, but the proposed syntax removes repetitive variable references?

That’s because my proposal is just quality of life, nothing game changing.

Does the syntax have to be ===?

No I think === is a placeholder, maybe something like @= but from here I think its up to you to decide.

How would this work?

I personally think this should be the exact same effects as doing variable = variable.lower() (or other methods), I also want to bring up the fact that some methods like .sort() don’t work on variable = variable.sort() and I propose it should stay that way for this to keep it readable and identical to the longer version.

Why would python benefit from this?

This is a simple quality of life improvement which could improve readability and improve speed of typing. Stuff like username = username.strip().lower().replace(“l”, “1”) will do the same thing in the same amount of lines but my proposal does it in fewer characters and makes it more readable.
About the person with the idea:

I am new to python (around OOP stage) so this idea will be rough around the edges, I don’t have amazing skills or anything this was just a random thought, I’m sure i have got something incorrect on the technical side, feel free to comment with suggestions for this idea or corrections. Contact me at lachlan-the-DEV github, proposed 6/11/2026.

Thanks for reading

Bye!
