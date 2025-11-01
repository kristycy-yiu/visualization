Visualization 2
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I used Python to code my data visualization.

    > Who is your intended audience? 
    My intended audience is individuals who are interested in historical fuel price trends, such as professionals in the oil industry or budget-conscious households. They may want to understand the long-term changes and seasonal fluctuations in fuel prices.
    
    > What information or message are you trying to convey with your visualization? 
   The visualization highlights differences in fuel prices across months between 1990 and 2000.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Colour: I used a colourblind-friendly palette to ensure that each line representing a different year is easily distinguishable, maintaining readability for viewers with colour vision deficiencies.
    Line styles and markers: I applied different line styles and markers for each year so that trends remain clear even if the reader is viewing in black and white.
    Text and labels: I ensured that all axes, titles, and legends are clearly labeled, with font sizes large enough for easy readability.
    Axes formatting: I extracted months from the date to use as the x-axis, simplifying interpretation and avoiding clutter from full date values.
    Legend: I included a clear legend so that viewers can easily associate each line with the correct year.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    My data visualization is fully reproducible because I included my Python code which outlines each step taken to process the data and generate the plot.

    > How did you ensure that your data visualization is accessible?  
    I ensured that my data visualization is accessible by considering the impact of colours (choosing colours from the colorblind palette), describing visual elements (legend), and ensuring the font sizes are big enough to see.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Individuals planning activities with high fuel consumption, such as road trips, might initially interpret seasonal price trends in 1990 as significant (lower prices in the winter Jan-Mar). Comparing with 2000, they can see that seasonal fluctuations are minimal, indicating that fuel prices are less of a factor for timing such trips. The less pronounced seasonal trends in fuel prices in 2000 may suggest market stabilization or other economic changes since 1990.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on a single region (Toronto West) to avoid clutter and reduce cognitive load, making it easier for users to compare two years without being overwhelmed by multiple regions.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Several preprocessing steps contributed to the final visualization: I created new data columns for the years of interest, separated the date into month and year for better x-axis representation, converted the fuel price from cents to dollar amounts to make the data more interpretable, and formatted the x-axis to show months instead of full dates for easier comparison.