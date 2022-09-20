# neoPrompt
a bash script to allow the user to easily type and/or paste text with an arbitrary number of lines to be used as prompts for gpt-neox 20B


  8/05/2022 - neoPrompt

       A bash script to allow a user to type and/or copy and paste large 
       amounts of text (single or multiple lines) to be used as prompts 
       for gpt-neox 20B : https://github.com/EleutherAI/gpt-neox

       A while true loop allows user to continuously paste
       in new text after each output.

  -------------------------------------------------------------------------------

  9/19/2022 - prompt variables & conda (and more comments)
  
       Added an initial 'proof of concept' for the script to show how 
       prompt variables may be used to generate better outputs. 

       As of now, starting your prompt with "#Q" will define your prompt 
       as a question and will start the prompt with with the text:
       "Trending Question: " and end it with "Top Rated Answer: "

       This will allow for easier question based prompting.
       This specific prompt variable may change and/or new prompt
       variables will be added if and when better prompting methods 
       are discovered.

       Incorporated conda environment into script for ease of use. 
       My neox conda environment list can now be found in the neoPrompt repository

       more comments have been added to explain certain lines :)
