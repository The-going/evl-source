# The EVL Project

The EVL project is about introducing a simple, scalable and 
dependable dual kernel architecture for Linux.
Details are written on this page: https://evlproject.org/

# EVL patches for the Linux kernel
from https://www.kernel.org/

Folders - 'patches.dovetail' and 'patches.evl-only' contains unnumbered patches.
'patches.dovetail' contains patches from the 'origin/dovetail/master' branch.
'patches.evl-only' contains only EVL real-time core patches.
The sequence of applying patches in a series is found in the files
'series.dovetail' and 'series.evl-only', respectively. First, apply
'patches.dovetail' then patches 'patches.evl-only'.
These two sources are intended primarily for transferring the current
version of the 'EVL' kernel to another version of the Linux kernel using the
'quilt' and 'git quiltimport' tools.

Folder - 'patches.evl' contains a complete series of numbered patches
from the 'origin/evl/master' branch GIT repository:
https://git.evlproject.org/linux-evl.git.
The sequence of which is contained in the file series.evl. This folder and file
are Packed in a single archive for easy downloading if you don't need everything.

You can completely restore the contents of this branch by applying the entire
series of patches use the 'git am' or 'git quiltimport' command to access the
newly created git repository from the archive by downloading the corresponding
version from: https://mirrors.edge.kernel.org/pub/linux/kernel/
