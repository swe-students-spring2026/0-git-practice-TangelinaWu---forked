# Deep Learning and Sports Technology

[Deep Learning for Automated Video Assistant Referee System (VARS) in Football](https://kilthub.cmu.edu/articles/poster/Deep_Learning_for_Automated_Video_Assistant_Referee_System_VARS_in_Football/26169517?file=47414146)

**Authors:** Ahmad Alhallaq, Ahmed Issaoui (2024)

---

## My Thoughts

I found this article interesting because it shows how artificial intelligence and deep learning are being applied to professional sports, specifically football refereeing. VAR has already changed how games are officiated, but this paper explores how automation could further reduce human bias and improve decision-making speed. Instead of relying entirely on referees to manually review footage, the system analyzes multiple camera angles and attempts to classify fouls and their severity automatically. What stood out to me was how complex this task is. Even with advanced deep learning models and thousands of video clips, the system still struggles to reach high accuracy.Lots of issues like limited data, unbalanced datasets, and video quality affect current performance. 

One aspect I found especially interesting was how the system uses multi-view video analysis. By combining footage from different camera angles, the model can better understand player interactions and fouls. What stood out to me most was the gap between the system’s potential and its current performance. According to the poster, the model achieved around 53% testing accuracy, which shows that while the approach is promising, it is not yet reliable enough for real-world deployment. 

## PR Comment

The supervised model’s performance is fundamentally constrained by limited data, which is an issue can only be solved by a significant commitment and time. It is therocially possible, but realistically not very feasible. It'll require astronmically more data to improve. I don't find it likely that any organization is willing to pour that much time or resources into data collection. Maybe it is better to consider unsupervised solutions, but of course it'll have its own problems when it comes to meaningful experimentation during the training stage, especially in a sport with many variables.
