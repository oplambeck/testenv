
=====
testenv
=====

This is a dummy package to test the in development functionality of MasonPublish.chpl which will be turned into a mason publish command. 

To run and test simply run ./MasonPublish

This represents a new mason package that someone wants to publish to the mason-registry, so it first clones the mason-registry and then creates a branch in which to add the new package. Then it adds the Mason.toml of the testenv to the mason-registry branch. Then adds a source field into the .toml that points to the testenv package repo. Finially the a new pull-request is created to merge the branch with the mason-registry.
