# A full workflow Shiny App
### <span style="color:#003368">**This app demonstrates the basic work flow from data entry to dynamic report. This display might be useful to create and host a small-scaled data platform and reporting system **without incorporating Database** such as documenting team projects progress or monthly or weekly marketing performance platform.**</span>

#### <span style="color:#003368">Data Entry: Users can add (modify, delete) data directly from the interface end.</span> 
####  <span style="color:#003368">Data Visualization: Users can drill down specific category by clicking the pie in the pie chart. Clicking "Back" to turn back to previous view. </span>
####  <span style="color:#003368">Dynamic Reporting: Users can write down their comments and download reports in pdf, word or presentation. </span>

Live app: https://appforiarteam.shinyapps.io/Shiny_Plotly/ 

* Log in
![gif1](Login.gif)

* Data Entry from UI side
Note: Here is a DT editor shiny module that can fit for any data.table. You just need to create your data.table and load it to the same location of your shiny app as note.rds Repo: https://github.com/jienagu/DT_editor_shiny_module
![gif2](Entry.gif)

* Drill down (interactive data visualization)
![gif3](Drill.gif)

* Dynamic Report
![gif4](Report.gif)

* Dynamic Presentation
![gif5](Presentation.gif)


### Acknowledgement

Inspired by a post from @cpsievert on @rstudio community forum (https://community.rstudio.com/t/shiny-developer-series-episode-1-follow-up-thread/29491). 

