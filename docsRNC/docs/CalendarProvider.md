Calendar context provider component  
[(code example)](https://github.com/wix/react-native-calendars/blob/master/example/src/screens/expandableCalendar.tsx)
:::info
This component extends **[Context](https://reactjs.org/docs/context.html)** props.
:::
<div style={{display: 'flex', flexDirection: 'row', overflowX: 'auto', maxHeight: '500px', alignItems: 'center'}}></div>

## API
### theme
Specify theme properties to override specific styles for calendar parts  
<span style={{color: 'grey'}}>Theme</span>

### style
Specify style for calendar container element  
<span style={{color: 'grey'}}>ViewStyle</span>

### date
Initial date in 'yyyy-MM-dd' format  
<span style={{color: 'grey'}}>string</span>

### onDateChanged
Handler which gets executed when the date changes  
<span style={{color: 'grey'}}>(date: string, updateSource: UpdateSource) => void</span>

### onMonthChange
Handler which gets executed when the month changes  
<span style={{color: 'grey'}}>(date: DateData, updateSource: UpdateSource) => void</span>

### disableAutoDaySelection
The calendar navigation type in which to disable the auto day selection (get options from ExpandableCalendar.navigationTypes)  
<span style={{color: 'grey'}}>CalendarNavigationTypes[]</span>

### showTodayButton
Whether to show the today button  
<span style={{color: 'grey'}}>boolean</span>

### todayButtonStyle
Today button's style  
<span style={{color: 'grey'}}>ViewStyle</span>

### todayBottomMargin
Today button's top position  
<span style={{color: 'grey'}}>number</span>

### disabledOpacity
The opacity for the disabled today button (0-1)  
<span style={{color: 'grey'}}>number</span>

### numberOfDays
The number of days to present in the timeline calendar (1-7)  
<span style={{color: 'grey'}}>number</span>

### timelineLeftInset
The left inset of the timeline calendar (sidebar width)  
<span style={{color: 'grey'}}>number</span>

