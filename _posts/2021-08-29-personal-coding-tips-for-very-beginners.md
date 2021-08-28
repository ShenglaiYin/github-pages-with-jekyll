# Personal experience for R coding tips
# Authored by: Dr. Shenglai Yin
# Date: 2021-08-28
# Reach the author: twitter: @Shenglai_Y; email: shenglai.yin@outlook.com

# At the beginning of a script, you'd better mark/comment (write done after #) the purpose(s) of this script.
# It helps other people to understand your code when they examine or re-produce your results
# It is also helpful to remind yourself about what you have done

# tips for writing in R studio, starts from here ----

# 1. use the following sign (lines 13-15) to separate your code; each separation for one (sub)purpose;
# code separate start ----
# the content in the separation; note the little down-pointing arrow on left side
# code separate end ----

# 2. for beginner, I highly recommend to write comments and explanation after your code (short, concise and precise); two advantages below
#   a. remind yourself what you are doing with this line of code, make afterwards check easier;
#   b. when you send your code to others (for communication or cross checking), it is easier for them to understand what you have 
#      done with the code

# 3. write short code, as short as possible

# 4. abbreviation should be easy for yourself ( and others ) to interpret and understand

# 5. writing consistently in UPPERCASE or lowercase, not change object names frequently

# 6. be brave and confident to play around with your code (or code from other). It would not bite you, but will definitely helps you to be familiar and understand it.

# 7. when you encounter a command or function that confuses you. Smile :) and check the R document. Normally, you see the 
#    explanations and example codes in details. If you are still confused, check the 10th tip below.

# 8. when you are dealing with complicated data processing process, I highly recommend you to draw flowchart to illustrate what and how
#    you gonna do. The flow chart should begin with your input data, end with your final output, piled up with processes of data processing

# 9. !!! always write in English, learn in English, read English materials

# 10. !!! get use to find solutions online, especially in English. In fact, nearly 90% of your questions, issues or problems
#        have been discussed by people all over the world, and the solutions have been put online. 

# 11. if you are fascinated by coding, Github will be your treasure cave. If you are not so interested in coding, using 
#     Github to do version control is also a great idea (Advanced tip). Do not know what is version control??? see the 10th tip (keep the 10th tip deeply in your mind)

# 12. always insert a space in the middles of two things/objects (e.g., between a character and # sign), except for brackets and dollar sign $.

# 13. in every step when you generate or process an object, check the object $$immediately$$ to see whether it was generated or processed in the way
#     you want, by using str(), head(), summary(), plot(), etc.

# 14. when you are applying others' code to your dataset, several things you need to pay attention:
#     a. you have to understand how, what and why of the code. Even you cannot 100% understand, but you HAVE TO know most of it
#     b. you have to examine the original dataset. The code you are borrowing is tightly tailored to the original dataset. It is very much likely that it cannot be
#        applied to your dataset directly (in most of cases). It is just like put others' cloth on you. It does NOT perfectly fit! So, always make a comparison 
#        between your data and the original. Make sure your dataset is reasonably comparable to the original dataset in size, 
#        data type (numeric or character), ncol, nrow, etc. If you need to make changes in the original code (in most of the cases you need to, trust me),
#        make sure you change the code throughly and correctly. 
#     c. ... ...

# 15. if you have multiple similar objects, and trying to discriminate them by adding postfix or prefix in the object name, make sure you adding the postfix or prefix
#     $$ALWAYS$$ at the same place (beginning, middle or end). Not to add them at the begining of some objects, but at the end of others. It will be confusing.

# TO BE CONTINUE...

