# ASCtoGraph
Converts ASC files into graphs for better visual interpretation. Current usage is primarily for interpreting IR spectra for different organic chemicals, but feel free to adapt to your own personal needs.

# Example
Say that I use a spectrometer to get the spectra reading of Benzil, but saved as an ASC file. 

edit line 63 (name = "Benzil") and make sure your ASC file is labeled with the same name as your chemical compound.
edit line 65 (a.settings_override()) if you would like to edit the domain of the graph to focus on specific area (for example 3000 cm^-1 for aromatic CH stretching)
call a.graph() to graph!

![image](https://user-images.githubusercontent.com/81098816/162226460-d721078a-a607-443d-af9d-bb4828cc46c8.png)

# Result

![image](https://user-images.githubusercontent.com/81098816/162226584-9b414ff5-e166-4823-a157-343e0676c44c.png)
