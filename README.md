# llm_wwii_journal_summary

### The Journal ###

My grandfather described his experiences as a soldier in the US Army's [48th Battalion](https://14thad.org/48thTankBattalion/index.cfm) in WWII in a handwritten journal he carried through France and Germany from 1944 to 1945. A few years after my grandfather passed away and my family was looking at his journal, I took photos of the all the pages to make sure we preserved the text. I also decided to transcribe the text into a Google doc and share with my family since physically handling the journal would only accelerate its deterioration.

![WWII Journal](https://images.squarespace-cdn.com/content/v1/5602c92ce4b08590f911d3a3/c38dac7c-93e9-4854-8978-46e8ef42a01e/IMG_1978.jpeg?format=2500w)

After completing the transcription, I noticed how abruptly the story ended. It was March 1945 and he was on his way back to his platoon in Lupstein, France after recuperating from an injury.

I'm not sure why he stopped.  My grandmother said after he arrived, his group was moving too fast for him to spend time writing. It's quite possible he thought he would pick up when he returned. But while I wanted to preserve the integrity his original text, leaving the story without a conclusion was unsatisfying.

### We Came to Fight ###

After the war ended and he returned home, the Army sent him a [book](https://14thad.org/48thTankBattalion/index.cfm#gallery-1), “We Came to Fight! - History from New York to Jettenbach”, recounting the 48th Battalion's experiences from training at Camp Campbell, KY to fighting in France and Germany until the announcement of VE Day in May 1945.

![We Came to Fight](https://images.squarespace-cdn.com/content/v1/5602c92ce4b08590f911d3a3/aee5e8ed-97fb-42e7-8f10-cb086d0de8a3/IMG_9798.jpeg?format=2500w)

I also transcribed the full text from this book since, like my grandfather’s journal, was not in good shape. Toward the end of the transcription, I realized I could just summarize the Battalion's activities from March to May as a conclusion to the journal. The problem was, the full text of “We Came to Fight” was greater than 11,500 words and I was too worn out from all the transcribing to attempt a summarization myself.

### LlamaIndex ###

Around this time, Jan 2023, I had discovered GPTIndex which is now [LlamaIndex](https://www.llamaindex.ai/). A tool for connecting text to LLMs, I decided it was a great option for generating the summary I was looking for.

While I generated the initial summary using GPTIndex and OpenAI's `text-davinci-003 model`, this notebook uses the 0.8.55 version of LlamaIndex and GPT-4 which produced more detail. If you're just getting started with LlamaIndex, these are some good examples of generating concise summaries.

Below is the original summary using GPT3 which produced an accurate summary over thousands of words. Check out the notebook for the GPT-4 examples.

*The 48th Tank Battalion was later attached to the 42nd Infantry Division, departed Lupstein and traveled 110 miles north and east across the Rhine River at Worms, Germany. Along the way, they encountered enemy planes, destroyed buildings, released Allied prisoners of war, and encountered resistance from the German Army. After reaching Neustadt, they moved south and joined forces with the Third Army and Seventh Army, driving towards Munich. They then moved to Bad Staffelstein, where they encountered more resistance and released more Allied prisoners of war. They then assisted the Third and 45th Infantry Divisions in seizing the city of Nuremberg and then cut the Autobahn south of the city in the vicinity of Neumarkt in der Oberpfalz. After contending with blown bridges, roadblocks, enemy artillery, mortar fire, anti-tank and small arms fire, they reached the town of Wildflecken. They then moved to Neustadt, where they consolidated their gains and posted, leading up to the announcement of VE Day, on May 8th.*
