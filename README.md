# Soji.AI-Engineer-test
result of my take home assignment.

FURTHER EXPLANATION
-The json is indeed to simulate database interactions, the select, insert in SQL DB. by saving and loading json i intend to simulate the database interaction along with following the requirements.
-The hurdle is while using pydantic is that i come across the realization that i do not know much in the regard of the document and aircraft law, i encountered problems caused by misunderstanding, i thought MSN_constraints was number of missions it cannot do so i put int instead of liststring. list because in practical setting there may be few MSN that are excluded instead of null or all. I took the time to discuss Airworthyness Directive topic and it's importance with Gemini.
-The direct comparation by Aircraft Model and MSN should give decisiveness to the analysis because AI having risk of hallucination and aviation industry deals with a lot of human lives.
-While indeed the current data loading from PDF is using AI, we can implement more direct analysis using Regex or other methods to grab the Aircraft Model and MSN, along with modification to provide a truth table for AI to work with, or to audit it's correctness.
-Asyncio is so the program works concurrently, saving time on waiting to time for program to do something. If we deploy in web service that counts compute time like Pythonanywhere this can save our billing seconds.
-Results can be refined, the functions are defined and can be modified as each work step have it's own function, for example the process_folder_pdfs function can be modified to use OCR model or VLLM. this would also put dubugging easier as we can put logging in each function to check for error more directly.
-Thank you for giving me the oppoturnity, if i am accepted i will have to learn ruling and law of aviation to make robust software to hasten aircraft check time while not forgetting safety and i request your understanding and guidance on this matter.
