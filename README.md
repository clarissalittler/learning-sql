# learning-sql

Here we'll going to collect links to various tutorials on learning SQL that I found good reads. I want to focus more on the general principles of relational databases and how to use query languages rather than on the specifics of a particular rdbms.

## Topics

A decent starting point for relational databases is the [wiki article](https://en.wikipedia.org/wiki/Relational_database). There's a few topics to cover in this document(s) (not so much things I'm going to write but topics I want to make sure that all the links cover)

  1. what's the point of relational databases? (we can presume that the need for databases is already obvious at this point)
     * probably don't bother with explaining why relational dbs vs. nosql approaches
     * a good place to start is the original paper by [Codd](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.94.5224&rep=rep1&type=pdf)
     * the original paper is a little opaque from its age, but it explains simple vs. non-simple data, primary and foreign keys, and the point of using a relational language for accessing the data rather than needing to know the internal structure 
  2. normalization of databases
     * review the various normal forms
     * explain why anyone *should care*
         * this has been a problem I've personally had in the past
  3. sql and what its operators are, probably covered largely in the [wikibook](https://en.wikibooks.org/wiki/Structured_Query_Language) on SQL
     * probably include exercises if at all possible
     * possibly include descriptions of *typed* operators just to include a bit more CS theory
         * e.g. give dependent typings for some of the basic operators
  4. the theory behind relational databases, i.e. [relational algebras](https://en.wikipedia.org/wiki/Relational_algebra)
     * a review of sets and their operations
         * sets-as-containers
         * cartesian products
             * projections thereof
         * disjoint sums
         * set comprehension notation
     * a review of boolean algebras
         * and
         * or
         * not
     * Converting simple sql queries to relational operations
         * [one document](http://www.databasteknik.se/webbkursen/relalg-lecture/index.html) found from wikipedia, academic formatting but the content isn't bad
     * [Lecture notes](http://www.nyu.edu/classes/jcf/CSCI-GA.2433-001/slides/session5/RelationalAlgebra-RelationalCalculus-SQL.pdf) on relational algebra and the distinction between it and SQL. Pretty comprehensive from first blush.
     * Also the wiki entry about [SQL and the relational model](https://en.wikipedia.org/wiki/Relational_model#SQL_and_the_relational_model)
         * tl;dr sql tables have specified column ordering and are multisets while the relational model is about equivalence classes of sets modulo ordering of the cartesian products
     


