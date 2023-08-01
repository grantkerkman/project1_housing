# project1_housing
grant_final coding notes
Line 2 I used all but the zori_df DataFrame in the coding, but only used the zhvi DataFrames to merge together. I was able to complete the analysis using the sale price instead of Zillow's proprietary valuation.

Line 5 Credit to a Medium blog with the idea of doing this. They had a prebuilt module with this code, but it was simple enough to just write into Juypter.

Line 22 I needed to look through Python documentation to figure out the odds and ends of the Transpose() function. Main idea was to transpose the DataFrame to be a column time-series. I believe I may have been able to use the original DataFrame and specify the rows as the default axis, but was running into issues making that happen. Mose of the issues I needed to consult Python documentation and ChatGPT were for the iloc functions to manipulate the columns.

General Note on the graphs I was attempting to create a user-defined function to generate any graph based on a given x and y variable. I had issues I was unable to resolve but now realize were likely due to where I was placing the plt.show() command. Regardless, copy/paste did the trick.
