The IVOA manages their Vocabulary Enhancement Proposals (VEP) through this
repository.  See `Vocabularies 2, Section 5.2`_ for what this is.

.. _Vocabularies 2, Section 5.2: https://ivoa.net/documents/Vocabularies/20210525/REC-Vocabularies-2.0.html#tth_sEc5.2.1 

Before starting a new VEP, it is probably a good idea to discuss your idea
on the `IVOA semantics mailing list`_.  Once you are ready to enter the
formal VEP process, do (the equivalents of):

.. _IVOA semantics mailing list: http://mail.ivoa.net/mailman/listinfo/semantics

* ``git clone https://github.com/ivoa/VEPs.git``
* Fork this repo on the github web page
* ``cd VEPs``
* ``git remote add mine git@github.com:<your user id>/VEPs.git``
* ``cp template.txt VEP-nnn.txt``; here nnn would be the next free
  number.
* Fill out ``VEP-nnn.txt``
* ``git add VEP-nnn.txt && git commit -am 'Adding VEP for ...``
* ``git push --set-upstream mine main``

Then create a PR using the github web page.  Please allow edits by the
maintainers; that helps keeping the commit history of the main
repository tidy.

VEPs can also be managed outside of github if authors have privacy
concerns.  Contact the chairs of the IVOA `Semantics WG`_ for more
information.

.. _Semantics WG: https://wiki.ivoa.net/twiki/bin/view/IVOA/IvoaSemantics
