[gimmick:yuml]( [Problem]needs -.->[Solution] )

~~ Qualifying questions ('bloodtest') ~~
( these would have to be answered to enable the algorithm section below )
~Q( "Has the patient received an organ transplant?" )

~~ Algorithm ('bloodtest') ~~
~I( "bloodcell_count", type: 'int', min: 0, max: 1000 )
~I( "some_percentage", type: 'percentage' )

~~ Logic ~~
if ~bloodcell_count > 50 AND ~some_percentage < 25 THEN
  ~SUGGEST( "Ask your docter to perform test XYZ" )
fi
~~ /Logic ~~

# Another example
Consider [this](https://www.aafp.org/pubs/afp/issues/2007/0301/p671.html) algorithm for diagnosis of iron deficiency anemia
