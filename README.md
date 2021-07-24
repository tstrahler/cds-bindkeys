# cds-bindkeys

This repository contains a *TeX* file for creating a tabular 
list of some bindkeys in *Cadence Virtuoso*.

The table contains figures of the corresponding toolbars-icons, 
which are not shipped in this repository.
Please link the icons from Virtuoso Installation directory
to the repository before compilation

```bash
ln -s `cds_root virtuoso`/share/cdssetup/icons
```

Afterwards, compile the Latex-File, e.g. using *pdflatex*

```bash
pdflatex cds-bindkeys.tex
```
