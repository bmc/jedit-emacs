Version 1.0.2 (31 January, 2011)

* The emacs_bindings.bsh startup logic now examines environment variable
  `JEDIT_SETTINGS_DIR`, using it as the location to search for the "macros"
   directory. Defaults to the standard jedit settings directory
   (e.g., `$HOME/.jedit`).

---

Version 1.0.1 (08 April, 2010)

* Removed all `print` statements from the BeanShell files. Robert Seward
  (*rseward /at/ bluestone-consulting.com*) indicated that they were causing
  errors with jEdit 4.3.1 and that removing them made jEdit happy again.

---

Version 1.0 (06 July, 2006)

* Initial public release.
