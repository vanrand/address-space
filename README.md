address-space
=============

Practical details of address space size


#### Idea

Create a simple web app which shows how big a given address size is (i.e. 32 bits, 40 hex-chars, 20 alpha chars, etc), including practical implications of that size, such as "[40 hex chars] 160 bits: large enough for every atom in the universe to have an address".

The original thought came to me when wondering the best sha1 size for a CAS system, keeping the length as low as possible while still eliminating the practical likelihood of a collision. This is different depending on how much content is likely to be created, is the system closed, etc. The standard Git 40 chars is way overkill and can be truncated much smaller, but how small is too small?

It would be cool to have a simple little JavaScript page with inputs and calculators to display all kinds of info regarding address space and size, hints and pointers, useful reference info, etc..
