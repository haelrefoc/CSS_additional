# CSS_additional
<p>
  <strong>CSS Sector for HTML:</strong><br>
p class="brand">XXXXXXX /p><br>
   h1 class="title">XXXX /h1><br>
    < !--You can also make your own sectors in style.css and then reference them later all at once in one HTML element in index.html to attribute multiple characteristics to a section in your code --><br>
    <i>Example</i> .green { xxx }<br>
                    .bold { xxx }<br>
                    h1 class="green bold"> xxx /h1><br>
                    < !--If an HTML element needs to be styled uniquely (no matter what classes are applied to the element), we can add an ID to the element. Normally, this is only meant to be used once. --><br>
                      #large-title { xxx }<br>
                      h1 id="large-title"> XXX /h1><br>
                      <p>
                        <strong>Important:</strong><br>
                        < !--This overrides everything --><br>
                          <i>Example:</i> p {<br>
                          color: blue !important;<br>
                          }<br>
                          .main p {<br>
                          color: red;<br>
                          }<br>
                          < !--!Important will override all p elements and make them blue, even though there is a .main p below that says red. --><br>
                        <strong>CSS Chaining Selectors:</strong><br>
                        <i>Example:</i> p.special { xxx }<br>
                        h1.special { xxx }<br>
                        h1 class="special"> XXX /h1>
                        < !-- These two .special tags do not have the same characteristics and only affect the element to which it is attached --><br>
                          <p>
                            <strong>Nested Elements:</strong><br>
                            <i>Example:</i> .main-list li { xxx }<br>
                            ul class="main-list"><br>
                            li> xxx /li><br>
                            li> xxx /li><br>
                            /ul><br>
                          <p>
                            <strong>Multiple Selectors:</strong><br>
                            < !--If two elements have the same style attributes, you cna combine them to save you time and code --><br>
                              <i>Example:</i> h1 {<br>
                              font-family: Georgia;<br>
                              }<br>
                              .menu {<br>
                              font-family: Georgia;<br>
                              }<br>
                              < !--This can actually be written like the following... --><br>
                                h1,<br>
                                .menu {<br>
                                font-family: Georgia;<br>
                                }<br>
                                
  
                                                      
                        
                      
                     
                
                    
                
            
