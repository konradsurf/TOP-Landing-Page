# TOP-Landing-Page
Landing page project from The Odin Project - part of the Foundations course

What I learned:

Navigation:


UL of links:  
Bulletpoints are removed in the styling of the UL while underlining of links is removed on the <a> element level.


Used margin for spacing in hero section between content on left and image on the right.  
There are mixed opinions on SO and other sites whether this or empty div is best practice...... 

Font weights:
Had an issue with different weights after adding 900 weight font to the import (in addiiton to the 400 weight). Reason turned out to be due to using header tags - some default to bold and override inherited font weight. Solved by making explicit declaration in those header tags to override the default bold setting. 