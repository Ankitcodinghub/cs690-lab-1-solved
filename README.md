# cs690-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CS690 Lab 1 Solved](https://www.ankitcodinghub.com/product/cs690-lab-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118175&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS690 Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Introduction:

Most OS code is written in C. Having a good understanding and practice in C will help you better understand code in our readings. In this homework you are to write in C your own static library for dynamic allocation using freelists

(Reference for Memory API: https://pages.cs.wisc.edu/~remzi/OSTEP/vm-api.pdf , Reference for FreeList: https://pages.cs.wisc.edu/~remzi/OSTEP/vm-freespace.pdf).

You should write this library in standard C99 on a Linux/Unix system using mmap.

The library should allocate (i.e., malloc) and deallocate (i.e., free). It does not have support growing the “heap” if out of memory (make the default mmap large enough to do a few mallocs). The first Fit strategy for selection is fine to use. Freeing memory should only combine segments if they are right next to each other. No need to recursively combine segments as this is just a toy library.

This is a reference on using ar to build a static library that can be linked against (https://tldp.org/HOWTO/Program-Library-HOWTO/static-libraries.html).

Point Breakdown:

I do not provide a point breakdown for this. The reason for this is that it will really depend on the submissions as this lab varies so much from year to year. However, the points will be mainly based on the percentage of correctness of the code.

Turn in:

The turn in should include a zip containing:

1. The library code (mymalloc.c and mymalloc.h).

2. The library (mymalloc.a)

3. A driver / tester program (main.c)

4. A Makefile that can both make the library and make the driver that is linked to the library (GNU Make, not CMAKE, etc).

5. A README that examples how to build and use.

It can be very tiny, e.g., %make lib; make main; ./main.exe

Linux Resources.

The department offers a number of Linux resources for students that do not have access. With you CS department login and VPN you can access:

Servers listed at this link (http://www.cs.uah.edu/intranet/content/kb/ssh.html) are: catalina.cs.uah.edu conquest.cs.uah.edu crusader.cs.uah.edu dakota.cs.uah.edu duchess.cs.uah.edu havoc.cs.uah.edu hawker.cs.uah.edu invader.cs.uah.edu lightning.cs.uah.edu marauder.cs.uah.edu shrike.cs.uah.edu

whirlwind.cs.uah.edu
