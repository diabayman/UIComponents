### Bubble Charts options

| Option        | Default value   | Description   | Type | Required   |
| ------------- |:-------------:|:-------------:|:-------------:|:----------|
 options | {"displayModeBar": false,"modeBarButtonsToRemove":[], "displaylogo": false,"modeBarButtonsToRemoveWrapper":{"toImage": true,"hoverClosestCartesian": true,"toggleSpikelines": true,"pan2d": true,"zoom2d": true,"resetScale2d":true,"select2d":true,"lasso2d":true,            "hoverCompareCartesian":true,"autoScale2d":true,"zoomOut2d":true,"zoomIn2d":true},"scrollZoom":false,"editable":false,"staticPlot":false},| options configuration | object | NO
 traces-config | [{"name":"trace0","marker":{"color": "rgb(93, 169, 214)","opacity": 1,"symbol": "square","line":{"color": "rgb(120,120,120)","width": 2}},"hoverlabel" : {"bgcolor":'#C8CE1B'},},{"name":"trace1","marker": {"sizeref": 2,"color": "rgb(93, 164, 214)"},"hoverlabel":{"bgcolor":'#C8CE1B'},}]|  configuration of the traces | array | NO
 layout-config | {"title":"The default of the graph","showlegend":false,"margin":{"l":140,"r":40,"b":50,"t":80},"xaxis":{"showline": true,"showgrid":false,"title":"Title of xaxis","linecolor":"rgb(204, 204, 204)","ticks":"outside","autotick": false,"dtick": 0,"tickcolor":'rgb(102, 102, 102)'},"yaxis":{"showline": true,"showgrid":false,"title":"Title of yaxis","linecolor":"rgb(204, 204, 204)","ticks":"outside","autotick": false,"dtick": 0,"tickcolor":'rgb(102, 102, 102)'},"hovermode": 'closest',"paper_bgcolor": 'rgb(253, 254, 254)',"plot_bgcolor": 'rgb(253, 254, 254)',"legend":{"font":{"size":10},"yanchor":"top","y":0.99,"xanchor":"left","x":0.01,"orientation":"v"}},| configuration of the layout | object | NO
  api | null | Name of the API to get data | string | Required if getting data from backend 
  on-format-data | null | Callback function to be called after data is returned from backend | function | NO
  transport |  'wss'     | 	method used to call api (can take "https" or "wss").	 | string | NO
  msg-tag   | null      | 	Subscribe to socket messages with tag name.		     | string | NO
  api-params  | null      | 	api parameters.  					| object | NO
  fetch-data-interval |  null     | 	the refresh interval in case of https transport.	 | int | NO
  use-window-params |  null     | 	If true the widget will merge the defined api-params with the params passed in the URL query params	 | boolean | NO
  
For more info, visit the following links if you wish to add more attributes to the above objects :
**traces-config** : <https://plotly.com/javascript/reference/scatter/>
**layout-config** : <https://plotly.com/javascript/reference/layout/>
**options** : <https://plotly.com/javascript/configuration-options/>
