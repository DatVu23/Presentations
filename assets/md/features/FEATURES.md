@snap[north span-100 text-pink]
Media Features is similar to Css Properties
@snapend

@snap[west span-100]
@ul[ text-05]
- Properties are used in declarations to give information about how to present a document. Media features are used in expressions to describe requirements of the output device
- Most media features accept optional ‘min-’ or ‘max-’ prefixes to express "greater or equal to" and "smaller or equal to" constraints. This syntax is used to avoid "<" and ">" characters which may conflict with HTML and XML. Those media features that accept prefixes will most often be used with prefixes, but can also be used alone.
- Properties always require a value to form a declaration. Media features, on the other hand, can also be used without a value. For a media feature feature, (feature) will evaluate to true if (feature:x) will evaluate to true for a value x other than zero or zero followed by a unit identifier (i.e., other than 0, 0px, 0em, etc.). Media features that are prefixed by min/max cannot be used without a value. When a media feature prefixed with min/max is used without a value it makes the media query malformed.
- Properties may accept more complex values, e.g., calculations that involve several other values. Media features only accept single values: one keyword, one number, or a number with a unit identifier. (The only exceptions are the ‘aspect-ratio’ and ‘device-aspect-ratio’ media features.)
@ulend
@snapend