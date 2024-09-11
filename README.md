# tg_annotation
The processing of TextGrid (Praat) and Seg (WaveAssistant) annotation.

# Short description
The module contains classes and methods to read/write, create and process TextGrids, Point- and IntervalTiers.


# Classes
**Point** - represents a labeled point in time. There is a possibility to compare time positions of points, do simple arithmetic operations in time domain.

**Interval** - represents a labeled interval in time. There is a possibility to compare time positions of points, do simple arithmetic operations in time domain, concatenate intervals.

**PointTier** - represents a labeled point tier as a list of points. There is a possibility to iterate through points, to index tier, to read/write Praat or Seg format file.

**IntervalTier** - represents a labeled interval tier as a list of intervals. There is a possibility to iterate through intervals, index tier, read/write Praat or Seg format file.

**TextGrid** - represents a labeled textgrid as a list of tiers. There is a possibility to iterate through tiers, index textgrid with position or tier name, read/write textgrid TextGrid file.

For usage instructions, see in-code documentation for classes.


