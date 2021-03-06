- 2018-06-14: Fixed a bug, UFO file format version must be an ``int``.
- 2018-06-20: Fixed a bug in ``world.AllFonts``

0.7.0 (released 2018-06-11)
---------------------------

- 2018-06-08: Fixed a bug in ``__bool__`` in ``Image`` that would fail if there was no image data.
- 2018-06-08: Fixed a bug in setting the parents in appending a ``guideline`` to a ``Glyph`` or ``Font``.
- 2018-05-30: Fixed a bug in both the base and fontshell implementations of ``groups.side1KerningGroups``.
- 2018-05-30: Fixed a bug in both the base and fontshell implementations of ``groups.side2KerningGroups``.
- 2018-05-30: Fixed a several bugs in ``BaseDict`` that would return values that hadn't been normalized.
- 2018-05-30: Implemented ``font.__delitem__``
- 2018-05-30: Implemented ``font.__delitem__``.
- 2018-05-30: Implemented ``layer.__delitem__``.
- 2018-05-30: ``font.removeGlyph`` is now an alias for ``font.__delitem__``.
- 2018-05-30: ``layer.removeGlyph`` is now an alias for ``layer.__delitem__``.
- 2018-05-30: ``font.insertGlyph`` is now an alias for ``font.__setitem__``.
- 2018-05-30: ``layer.insertGlyph`` is now an alias for ``layer.__setitem__``.
- 2018-05-30: ``font.appendGuideline`` now accepts a guideline object.
- 2018-05-30: ``glyph.copy`` uses the new append API.
- 2018-05-30: ``glyph.appendGlyph`` uses the new append API.
- 2018-05-30: ``glyph.appendComponent`` now accepts a component object.
- 2018-05-30: ``glyph.appendAnchor`` now accepts and anchor object.
- 2018-05-30: ``glyph.appendGuideline`` now accepts a guideline object.
- 2018-05-30: ``contour.appendSegment`` now accepts a segment object.
- 2018-05-30: ``contour.appendBPoint`` now accepts a bPoint object.
- 2018-05-30: ``contour.appendPoint``  now accepts a point object.
- 2018-05-30: ``contour.insertSegment`` now accepts a segment object.
- 2018-05-30: ``contour.insertBPoint`` now accepts a bPoint object.
- 2018-05-30: ``contour.insertPoint`` now accepts a point object.
