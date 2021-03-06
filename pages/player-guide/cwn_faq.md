---
title: Frequently Asked Questions
keywords: faq
summary: "Answers to frequently asked questions"
sidebar: cwn_sidebar
permalink: cwn_faq.html
toc: false
folder: player-guide
---

<p>If you want to use an FAQ format, use the syntax shown on the faq.html page. Rather than including code samples here (which are bulky with a lot of nested <code>div</code> tags), just look at the source in the mydoc_faq.html theme file.</p>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">1: Harder</a>
                            </h4>
                        </div>
                        <div id="collapseOne" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                That's what you need to Try.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">2: Who muchz atention too deetalez shoudl i halveszes?</a>
                            </h4>
                        </div>
                        <div id="collapseTwo" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                Attention to detail is paramount. Read the example input and expected output VERY CAREFULLY. Then plan for the worst. Don't expect that you can just slam-code your way through a challenge. If you look at the challenge name(most times a hint), the problem description, the example input and output, it will give you a good starting point. You MUST also come up with extra input to test your logic! If you only test your code against the example data, and nothing else, then you will probably get incorrect output upon submission.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseThree">3: Test data?</a>
                            </h4>
                        </div>
                        <div id="collapseThree" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            You need to verify the logic in your programs by generating your own test input data sets! We have provided you with a small set of example input data. The expected output we give you in the challenge will show you the proper ordering and formatting. Ensure you do thorough testing against your programs! If not you will probably keep getting incorrect output..... If you do, generate more test data and verify!
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFour">4: Where do I register as 5up3r1337H4xX0R?</a>
                            </h4>
                        </div>
                        <div id="collapseFour" class="panel-collapse collapse">
                            <div class="panel-body">
                            Usernames and passwords were initially predefined, we have now added the ability for you to be able to change your passwords to whatever you would like. If you would like to change your password, click on your username in the top right corner of the webpage. However if you would like your username to changed to something like 5up3r1337H4xX0R, we will make fun of you.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFive">5: Where are all the boxes that I'm supposed to pwn?</a>
                            </h4>
                        </div>
                        <div id="collapseFive" class="panel-collapse collapse">
                            <div class="panel-body">
                            <p>
                            This is a programming competition, not a hacking competition. Attempting to hack or doing anything malicious to the server infrastructure or anything on our networks is strictly forbidden! Everything is logged and we take every malicious attempt no matter how small very seriously. Anybody caught doing anything malicious will be immediately removed from this site and will not be allowed to participate in any future competitions of any type. Also rest assure we will submit all malicious findings to the proper authorities.
                            </p>
                            <p>
                            Let it be known, YOU DO NOT HAVE PERMISSION TO PERFORM ANY ACTION OUTSIDE THE SCOPE OF TRYING TO SOLVE A CHALLENGE. This includes any "testing" of the defensive posture of this site/application. Neither are you allowed to attempt to initiate connectivity with any of the servers associated with CodeWarz by any other means than those provided (as intended) with the web interface (socket.socket(); connect('bleh.biz') is pretty frowned upon). That is to say, do not attempt to exfil data, spawn a reverse shell, or whatever. Not only will it not work, but we will take appropriate action where necessary. By using this site you agree to all the items on this page, as well as our legal page.
                            </p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSix">6: What happens if my visual basic gui for backtraces breaks the server?</a>
                            </h4>
                        </div>
                        <div id="collapseSix" class="panel-collapse collapse">
                            <div class="panel-body">
                            Your code is ran on an isolated machine from the front end web server. The isolated machine that runs your code, runs it inside an isolated(sandboxed) docker container. The only thing you can break is your own environment. If it happens, we will look at the code you submitted and the admins will make a judgement call on whether to fix it or not. If you feel you that you broke something, please reach out to an admin and let us know. Pretty sure we are catching any possible exceptions, but you never know. If the breakage is intentional then you will most likely have your access to the game revoked. This will be a judgement call by the admins.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSeven">7: I submitted like 500 programs but only got feedback on 126 of them, why is the backend broken?</a>
                            </h4>
                        </div>
                        <div id="collapseSeven" class="panel-collapse collapse">
                            <div class="panel-body">
                            Your submitted code entries will run in parallel. Some of the tests your code will be run against may take some time. Not all of the problems consist of reading a few lines of text and printing them. Also, if you have a while loop that never exits, you are slowing down available resources for yourself and others. Try not to use while loops unless you absolutely need to. If you need to use them, make sure you have a proper exit condition for your while loop. Ensure you test your code locally before submitting it to the server. Time is of the essence in this competition. Your code has a maximum run time of five minutes. If you code takes longer than five minutes to run you will get a died while running error at the end of the five minutes from your code being submitted.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseEight">8: I made the most boss python script, why does the server tell me it's not the correct file type?</a>
                            </h4>
                        </div>
                        <div id="collapseEight" class="panel-collapse collapse">
                            <div class="panel-body">
                            You must ensure proper file extensions for your submitted scripts/code. For example if you have a hello world script written in python named hello_world.txt, this will not execute and fail as the server expects a .py for python scripts.
<code><pre>For Reference: bash == .sh ; c == .c ; c++ == .cpp ; clisp == . lsp ; golang == .go ; haskell == .hs
               perl == .pl ; nodejs == .js ; python == .py ; php == .php ; ruby == .rb ; scala == .sh</pre></code>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseNine">9: I couldn't figure out how to install linux, will my CRLF ridden code work?</a>
                            </h4>
                        </div>
                        <div id="collapseNine" class="panel-collapse collapse">
                            <div class="panel-body">
                            The only changes that occur to your code from submission to grading are that they are run through dos2unix. This fixes your newline situations and does absolutely nothing for the folks submitting code written on a linux/mac box except add a few extra milliseconds of time.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTen">10: What is my code run against?</a>
                            </h4>
                        </div>
                        <div id="collapseTen" class="panel-collapse collapse">
                            <div class="panel-body">
                            Your code/program will be run against a plain text file or command line arguments. If it is a text file, it will contain the data outlined in the 'Expected Input' section of the challenge. This being said, your code should be able to read data from a file being served up as ARGV[1] as such (in python, other languages will vary):
                            {% highlight python %}
#!/usr/bin/env python
import sys
infile = sys.argv[1]
with open(infile) as f:
do_stuff()
                            {% endhighlight %}
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseEleven">11: Where is $language_interpreter installed so I can format my shebang correctly?</a>
                            </h4>
                        </div>
                        <div id="collapseEleven" class="panel-collapse collapse">
                            <div class="panel-body">
c (gcc 5.4.0):
<pre>
No shebang needed, just name the file ending in .c
</pre>
c++ (g++ 5.4.0):
<pre>
No shebang needed, just name the file ending in .cpp
</pre>
clisp (2.49):
<pre>
#!/usr/bin/env clisp
</pre>
golang (1.9.2):
<pre>
No shebang needed, just name the file ending with .go
</pre>
haskell (2014.2.0):
<pre>
No shebang needed, just name the file ending with .hs
</pre>
perl (5.22.1):
<pre>
#!/usr/bin/env perl
</pre>
nodejs (9.2.0):
<pre>
#!/usr/bin/env node
</pre>
python (2.7.12):
<pre>
#!/usr/bin/env python
</pre>
python3 (3.5.2):
<pre>
#!/usr/bin/env python3
</pre>
python3 (3.6.3):
<pre>
#!/usr/bin/env python3.6
</pre>
php (7.1.11):
<pre>
#!/usr/bin/php
</pre>
ruby (2.3.1p112):
<pre>
#!/usr/bin/env ruby
</pre>
scala (2.11.6-6):
<pre>
#!/usr/bin/env scala
</pre>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwelve">12: I just learned to count but.. What is a number?</a>
                            </h4>
                        </div>
                        <div id="collapseTwelve" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            Numbers are ints, floats, negative, positive... you name it. Keep these considerations in mind when you read the challenge data and while coding up your solutions.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseThirteen">13: My code keeps getting incorrect match what gives?</a>
                            </h4>
                        </div>
                        <div id="collapseThirteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            Well first off you better make 100% certain that your program exactly matches the output of the example. If your program does not match that, then it will definitely fail against the other sets of data that we test your program with. A helpful hint about your program, we give you a small sample of example input data, however we don't show you everything we test against. So it would be smart if you tested your program against more than just our example data set. Especially things that could possible cause your program to break IE: white space, new lines, integers, floats, negative numbers, etc, etc, etc. Test your program/code against all the types of input data as indicated in the problem statement and the example input data (together they paint a complete picture); there is a good chance that the example input data does not indicate all of our testing.

                            You can use this handy one liner to compare the output of your program's output to the example input.
{% highlight bash %}
diff -yW"`tput cols`" expected_output.txt my_solve_output.txt
{% endhighlight %}
                            Whitespace at the end of your output does not matter. All output (both yours, and the expected) are run through .strip() prior to comparison. If your output ends with 'ohai\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n' it will be compared as 'ohai'.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFourteen">14: You mention matching against english words. I failed my American class, what do?</a>
                            </h4>
                        </div>
                        <div id="collapseFourteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            There is a wordlist available at This link! Alternatively, on your own linux box (debian based distros) you can probably do something like:
{% highlight bash %}
sudo apt-get install wamerican
{% endhighlight %}
Which will install that same file into /usr/share/dict/american-english.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFifteen">15: I'm a Brute, and I like to force things.</a>
                            </h4>
                        </div>
                        <div id="collapseFifteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            If a challenge should be solved via brute force, it will be marked as such. If you think that's the only way to solve a challenge and it is not marked as 'BRUTE FORCE IS NECESSARY' then you need to rethink your plan. If you are caught attempting to brute force a solution to a non brute force challenge then the administration will most likely lock your account at the very least, or possibly even remove your access to the game. Tread lightly.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSixteen">16: What is an "Expected Hash"?</a>
                            </h4>
                        </div>
                        <div id="collapseSixteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
The Expected Hash listed on an individual challenge page is the sha1 hash of the expected output from the example data given. If you hash your test answer, it should match the hash given. Keep in mind that things like leading and trailing spaces/newlines (very beginning and very end) won't really matter as your output as well as the expected output are passed through python's .strip() function.</br></br>
Try this handy one liner to see if your hashes match the hash on the challenge page.
{% highlight bash %}
$ ./solve.py input_data1.txt | python -c "import sys,hashlib; print(hashlib.sha1(sys.stdin.read().strip()).hexdigest())"
{% endhighlight %}
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSeventeen">17: Why doesn't my language read input as expected?</a>
                            </h4>
                        </div>
                        <div id="collapseSeventeen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
The input data to our challenges are built with newlines stripped.  This can cause some problems in some languages like C, C++, BASH, etc... For example, if you try to read data made with:
{% highlight bash %}
echo -n "hello there" > test.txt
{% endhighlight %}
or
{% highlight bash %}
echo "hello there" > test.txt
{% endhighlight %}
you will get different results.  Please plan to read your data against input built with the first example.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}
