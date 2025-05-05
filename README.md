# cse3320-assignment3-develop-and-implement-a-small-unix-cp-m-like-file-system-fs-solved
**TO GET THIS SOLUTION VISIT:** [CSE3320 Assignment3-develop and implement a small Unix-CP/M-like file system (“FS”) Solved](https://www.ankitcodinghub.com/product/cse3320-assignment3-develop-and-implement-a-small-unix-cp-m-like-file-system-fs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;51706&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE3320 Assignment3-develop and implement a small Unix-CP\/M-like file system (“FS”) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
:

You will develop and implement a small Unix-CP/M-like file system (“FS”).

Your file system will not be part of an operating system, but, similar to&nbsp;&nbsp;&nbsp; modern file systems, it will run in several different operating systems to&nbsp;&nbsp;&nbsp; provide a “portable” file system.

&nbsp;

Details:

Your FS will use a file (for example “disk01”), rather than directly using&nbsp;&nbsp;&nbsp; a physical flash or disk, to store data.

You may have several disk-like files (for example: disk01, disk02),

used to store data. The data stored in disk01 may be a user’s programs, text files,&nbsp;&nbsp; other data files, or any type of binary information. In addition to the data&nbsp;&nbsp; stored, your FS will need to store other, meta-information, such as free space&nbsp;&nbsp;&nbsp; (blocks), directory details, and possibly other information. The FS directory is flat&nbsp;&nbsp;&nbsp; (one level) fixed sized, has a user name associated with each file, and has fixed&nbsp;&nbsp;&nbsp; sized “blocks” (entries).

You should use fixed size blocks (similar to disk blocks) of size 256 bytes to store&nbsp;&nbsp;&nbsp; files and all meta-data in your “disk”.

(Your “disk” (for example “disk01” is logically divided into a number of “sectors”,&nbsp;&nbsp; which are fixed size blocks. Everything that is stored (persistent) is in these&nbsp;&nbsp; blocks)

Your program (the “FS” executable) should provide the following operations:

Createfs #ofblocks – creates a filesystem (disk) with #ofblocks size, each 256 bytes

Formatfs #filenames #DABPTentries

Savefs name– save the “disk” image in a file “name”

Openfs name- use an existing disk image

List – list files (and other meta-information) in a FS

Remove name –remove named file from fs

Rename oldname newname – rename a file stored in the FS

Put ExternalFile – put (store) Host OS file into the disk

Get ExternalFile – get disk file, copy from “disk” to host OS file system

User name – this user owns this user’s files

Link/Unlink – Unix style file linking

Bonus: Set/Use file permissions for r/w/x, implement subdirectories, “check disk”

Implement in either the “Go” or “Rust” programming language (20 to 75 point bonus).

Implementation:

Your FS should have 4 (or more, if easier to implement) sections:

A FileNameTable (FNT), an directory and attribute/block pointer table (DABPT),&nbsp;&nbsp;&nbsp;&nbsp; and the data blocks.

The FNT should be of size allocated, each entry should contain a 56 char

(maximum) file name and an inode pointer (index to DABPT)(blocks).

The DABPT should be allocated from disk blocks, 4 entries per block, where each entry&nbsp;&nbsp;&nbsp;&nbsp; should contain a file meta-information (FileSize, last time+date (secs), “pointers”&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; to data blocks- (that is a pointer to the first entry in the Block Pointer Table),&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; and a user name (maximum length 40 characters)

The Block Pointer Table has direct pointers to data blocks, and one additional&nbsp;&nbsp;&nbsp; &nbsp;pointer to another entry in the Table, if needed (for big files), these may be&nbsp;&nbsp;&nbsp;&nbsp; chained for very large files. (Similar to CP/M extents), there is an array of sets&nbsp;&nbsp;&nbsp;&nbsp; (groups) of 8 pointers, of 32 bits each, and the last (8<sup>th</sup>) pointer can chain.

&nbsp;

Since disks (and some meta-information) are fixed size, many small or one&nbsp;&nbsp; large file might not fit on the “disk”. File names, file attributes and other file&nbsp;&nbsp; information stored in FS are restrictive (for example, file creation time).
