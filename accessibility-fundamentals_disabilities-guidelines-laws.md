# Accessibility Fundamentals - Disabilities, Guidelines, and Laws

## Types of Disabilities: Personas

### Blind

#### Design Considerations for Blindness
| Design Consideration | Why? |
| --- | ---
| Present all content (alt text, etc.) with a text equivalent. | Screen readers can't read non-text content so providing an alternative adds context | 
| Don't use visual attributes alone (color, spatial, thickness, etc.) to convey information | Some visual information, such as color and font weights, aren't available to screen readers |
| All functionality can be utilised and accessed via keyboard | Most visually impaired users can not easily make use of a mouse or trackpad. They will use keyboard navigation for everything. |
| Utilise correct and semantic markup | Screenreaders rely on semantic markup to provide context, but also allow users to navigate the page using headings, landmarks, controls, etc. |
| Try to stick to native HTML elements but when not possible, ensure that all custom controls have the appropriate name/label, role, value. They must also change / behave appropriately (e.g. aria-expanded = 'false' to true) | Screenreaders rely on the semantic parts / behaviours of native HTML elements. Not accounting for this when using custom elements means that non visual users won't be aware of the property updates of the elements. |
| Always immediately notify users after an action. | Examples are expanding or collapsing a region, changing a value on a control, form submission. Silence after activating a feature can be confusing and is never a good thing. |
| Add audio descriptions to videos if the original video audio doesn't provide all of the context required to understand the video | If the dialog of the video doesn't provide sufficient context and relies on visual queues, these need to be explained and provided for visually impaired users who otherwise won't fully understand the content. |
| Make sure all mobile features utilise a click action. | Screenreaders when used on mobile devices, make use of swipe actions to navigate. All features should require a click action so as not to interfere with the screenreader / break functionality of your site / app. |


