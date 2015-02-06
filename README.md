# BootstrapCollapse
Easy way to make use of bootstrap collapse component

# Get Started
$('#collapse').collapse(panel);

# Use a style
$('#collapse').collapse(panel, {style: Collapse.STYLE_DEFAULT});

There are 6 styles you can apply to a collapse

Collapse.STYLE_DEFAULT = 'panel-default';
Collapse.STYLE_INFO = 'panel-info';
Collapse.STYLE_PRIMARY = 'panel-primary';
Collapse.STYLE_SUCCESS = 'panel-success';
Collapse.STYLE_WARNING = 'panel-warning';
Collapse.STYLE_DANGER = 'panel-danger';

# Other Options
## collapse
default to true - expand the panel by default

# Events
All the events are executed in the Collapse context so you will be able to access all properties of a collapse

## beforeShow
Invoked before panel body is expanded

## postShow
Invoked after panel body is expanded

## beforeHide
Invoked before folding the panel

## postHide
Invoked after folding the panel
