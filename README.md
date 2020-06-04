# utl-identifying-the-html-table-and-exporting-to-spss-then-sas-scraping
Identifying the html table and exporting to spss then sas  
    Identifying the html table and exporting to spss then sas                                                                           
                                                                                                                                        
    github                                                                                                                              
    https://tinyurl.com/y98o3yc7                                                                                                        
    https://github.com/rogerjdeangelis/utl-identifying-the-html-table-and-exporting-to-spss-then-sas-scraping                           
                                                                                                                                        
    I use SPSS because V5 xport(max string 200 length) and stata(max string 244) do not                                                 
    support the 600 string length in this post.                                                                                         
                                                                                                                                        
    gitub                                                                                                                               
    https://tinyurl.com/ybqnmm5j                                                                                                        
    https://stackoverflow.com/questions/62027587/using-rvest-to-scrape-specific-html-table-using-the-heading-name                       
                                                                                                                                        
    dominik s meier profile                                                                                                             
    https://stackoverflow.com/users/6242132/dominik-s-meier                                                                             
                                                                                                                                        
    *_                   _                                                                                                              
    (_)_ __  _ __  _   _| |_                                                                                                            
    | | '_ \| '_ \| | | | __|                                                                                                           
    | | | | | |_) | |_| | |_                                                                                                            
    |_|_| |_| .__/ \__,_|\__|                                                                                                           
            |_|                                                                                                                         
    ;                                                                                                                                   
                                                                                                                                        
    I am interested in the 'task' table                                                                                                 
                                                                                                                                        
    This is the key string identifying the table is                                                                                     
                                                                                                                                        
    <th><b>Task</b></th>                                                                                                                
                                                                                                                                        
    https://www.nanaimo.ca/WhatsBuilding/Folder/BP125602                                                                                
                                                                                                                                        
    I have copied the key html code here.                                                                                               
    You can use the link if you like.                                                                                                   
                                                                                                                                        
    URL <- "https://www.nanaimo.ca/WhatsBuilding/Folder/BP125602";                                                                      
                                                                                                                                        
    filename ft15f001 "d:/htm/lonstring.htm";                                                                                           
    parmcards4;                                                                                                                         
    <table class="standard-table">                                                                                                      
    <tr>                                                                                                                                
    <th><b>Task</b></th>                                                                                                                
    <th><b>Status</b></th>                                                                                                              
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    PLAN CHECK COMPLETE                                                                                                                 
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     Signifies that the plan review is complete and the folder has been forwarded                                                       
    to the supervisor for approval.</span></p>                                                                                          
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    COMPLETED                                                                                                                           
    </td>                                                                                                                               
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    FOOTING / FORMS                                                                                                                     
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     Inspection of forms prior to any concrete being poured</span></p>                                                                  
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    PARTIAL                                                                                                                             
    </td>                                                                                                                               
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    FOOTING / FORMS                                                                                                                     
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     Inspection of forms prior to any concrete being poured</span></p>                                                                  
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    PASSED                                                                                                                              
    </td>                                                                                                                               
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    PERIMETER DRAIN                                                                                                                     
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     For perimeter drain , foundation walls should be damp proofed and drain tile in                                                    
    place with drain rock covering</span></p>                                                                                           
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    PASSED                                                                                                                              
    </td>                                                                                                                               
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    PERIMETER DRAIN                                                                                                                     
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     For perimeter drain , foundation walls should be damp proofed and drain tile                                                       
    in place with drain rock covering</span></p>                                                                                        
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    PARTIAL                                                                                                                             
    </td>                                                                                                                               
    </tr>                                                                                                                               
    <tr>                                                                                                                                
    <td>                                                                                                                                
    UNDERSLAB PLUMBING                                                                                                                  
    <p style="padding-top:4px; padding-left:2px"><span style='line-height: 120%'>                                                       
     Complete underslab plumbing must be visable</span></p>                                                                             
    </td>                                                                                                                               
    <td style='font-size: smaller;padding-left: 5px; border-style: none; width: 90px'>                                                  
    FAILED                                                                                                                              
    </td>                                                                                                                               
    </tr>                                                                                                                               
    </table>                                                                                                                            
    ;;;;                                                                                                                                
    run;quit;                                                                                                                           
                                                                                                                                        
    *            _               _                                                                                                      
      ___  _   _| |_ _ __  _   _| |_                                                                                                    
     / _ \| | | | __| '_ \| | | | __|                                                                                                   
    | (_) | |_| | |_| |_) | |_| | |_                                                                                                    
     \___/ \__,_|\__| .__/ \__,_|\__|                                                                                                   
                    |_|                                                                                                                 
    ;                                                                                                                                   
                                                                                                                                        
    p to 40 obs from WORK.WANT total obs=6                                                                                              
                                                                                                                                        
    Obs    TASK                                                                                                                         
                                                                                                                                        
     1     PLAN CHECK COMPLETE Signifies that the plan review is complete and the folder has been forwardedto the supervisor for approva
     2     FOOTING / FORMS Inspection of forms prior to any concrete being poured                                                       
     3     FOOTING / FORMS Inspection of forms prior to any concrete being poured                                                       
     4     PERIMETER DRAIN For perimeter drain , foundation walls should be damp proofed and drain tile inplace with drain rock covering
     5     PERIMETER DRAIN For perimeter drain , foundation walls should be damp proofed and drain tilein place with drain rock covering
     6     UNDERSLAB PLUMBING Complete underslab plumbing must be visable                                                               
                                                                                                                                        
                                                                                                                                        
                    Variables in Creation Order                                                                                         
                                                                                                                                        
    #    Variable    Type    Len                                                                                                        
                                                                                                                                        
    1    TASK        Char    598    *** use SPSS because it supports length of 2 billlion?                                              
                                    *** V% SASxport and STATA  will not work                                                            
                                                                                                                                        
    %utlfkil(d:/sav/want.sav);                                                                                                          
                                                                                                                                        
    proc datasets lib=work nolist;                                                                                                      
      delete want wantfix;                                                                                                              
    run;quit;                                                                                                                           
                                                                                                                                        
    %utl_submit_r64('                                                                                                                   
    library(rvest);                                                                                                                     
    library(data.table);                                                                                                                
    library(SASxport);                                                                                                                  
    library(haven);                                                                                                                     
    URL <- "";                                                                                                                          
    tables <- URL %>%                                                                                                                   
      read_html() %>%                                                                                                                   
      html_table("d:/htm/lonstring.htm");                                                                                               
    task_table <- lapply(tables, function(x) if(names(x) == "Task"){x});                                                                
    task_table[sapply(task_table, is.null)] <- NULL;                                                                                    
    task_table <- as.data.frame(task_table[[1]][["Task"]]);                                                                             
    want <- as.data.table(lapply(task_table, function(x) if(is.factor(x)) as.character(x) else x));                                     
    colnames(want)="task";                                                                                                              
    str(want);                                                                                                                          
    want$task<-gsub("[\r\n]", "", want$task);                                                                                           
    write_sav(want, "d:/sav/want.sav")                                                                                                  
    ');                                                                                                                                 
                                                                                                                                        
    proc import out=work.want                                                                                                           
      datafile='d:/sav/want.sav'                                                                                                        
      dbms=SAV replace;                                                                                                                 
    run;quit;                                                                                                                           
