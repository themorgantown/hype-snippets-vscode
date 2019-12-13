# GSAP Code Snippets README

This extension makes it easier to work on Hype JavaScript API functions in VScode. Learn more about [Tumult Hype here](https://tumult.com/hype/). View all JavaScript API functions on [this page](https://tumult.com/hype/documentation/#javascript).


## Snippets

Below is a list of all available snippets and the triggers of each one. The → means the TAB key.


| Trigger | Content |
|---|---|
| from→ | Create `from` tween. |
| fromTo→  | Create `fromTo` tween. |
| set→  | Create `set` tween. |
| stagger→  | Create `staggerTo` or `staggerFrom` tweens. |
| staggerFromTo→  | Create `staggerFromTo` tween. |
| tween→  | Create `TweenLite.to(elem, 1, {vars})` tween. |

## Release Notes

### 1.0

Initial release 

## todo


 GSAP EXAMPLES:[]

        {
            "from": {
                "prefix": "from",
                "body": "from(${1:elem},  ${2:1}, {${3:vars}}${4})",
                "description": "Create from tween.",
                "scope": ""
            },
            "fromTo": {
                "prefix": "fromTo",
                "body": "fromTo(${1:elem}, ${2:1}, {${4:fromVars}}, {${5:toVars}}${6})",
                "description": "Create fromTo tween.",
                "scope": ""
            },
            "set": {
                "prefix": "set",
                "body": "set(${1:elem}, {${2:vars}}$3)",
                "description": "Create set tween.",
                "scope": ""
            },
            "stagger": {
                "prefix": "stagger",
                "body": "stagger${1:To}(${2:elem}, ${3:1}, {${4:vars}}, ${5:0})",
                "description": "Create stagger tween.",
                "scope": ""
            },
            "staggerFromTo": {
                "prefix": "staggerFromTo",
                "body": "staggerFromTo(${1:elem}, ${2:1}, {${4:fromVars}}, {${5:toVars}}, ${6:0})",
                "description": "Create staggerFromTo tween.",
                "scope": ""
            },
            "to": {
                "prefix": "to",
                "body": "to(${1:elem}, ${2:1}, {${3:vars}}${4})",
                "description": "Create to tween.",
                "scope": ""
            },
            "Tween": {
                "prefix": "Tween",
                "body": "Tween${1:Lite}.${2:to}(${3:elem}, ${4:1}, {${5:vars}});",
                "description": "Create TweenMax or Lite.",
                "scope": ""
            }
        }

 done
 ${resourcesFolderName}

 done
 hypeDocument.documentName()

 
 				hypeDocument.documentId()



 				hypeDocument.resourcesFolderURL()
				
				
 				hypeDocument.functions()
				
				
 				hypeDocument.customData
				 
 				hypeDocument.getElementById()
			 
				 
		
                 hypeDocument.getElementProperty(element, propertyName)

 'top'
 'left'
 'width'
 'height'
 'rotateZ'
 'scaleX'
 'scaleY'
 'opacity'
 'z-index'
 'background-image'
 

 hypeDocument.setElementProperty()
				
                

 hypeDocument.relayoutIfNecessary()
				
                

 				hypeDocument.sceneNames()
				
                
 				hypeDocument.currentSceneName()
				
                
 				hypeDocument.currentSceneId()
				
                
 				hypeDocument.showSceneNamed()
				
 hypeDocument.kSceneTransitionInstant
 hypeDocument.kSceneTransitionCrossfade
 hypeDocument.kSceneTransitionSwap
 hypeDocument.kSceneTransitionPushLeftToRight
 hypeDocument.kSceneTransitionPushRightToLeft
 hypeDocument.kSceneTransitionPushBottomToTop
 hypeDocument.kSceneTransitionPushTopToBottom


 				hypeDocument.showNextScene()
				
                
 				hypeDocument.showPreviousScene()
				
                

 				hypeDocument.layoutsForSceneNamed('scenename')
				
                
 				hypeDocument.currentLayoutName()
				 
 				hypeDocument.showLayoutNamed()
				
                
 				hypeDocument.startTimelineNamed()
				
                
 				hypeDocument.pauseTimelineNamed()
				
                
 				hypeDocument.continueTimelineNamed()
				
                
 				hypeDocument.goToTimeInTimelineNamed()
				
                
 				hypeDocument.currentTimeInTimelineNamed()
				
                
 				hypeDocument.durationForTimelineNamed()
				
                
 				hypeDocument.currentDirectionForTimelineNamed('timelineName')
				
                

 				hypeDocument.getSymbolInstanceById()
				
                
 				hypeDocument.getSymbolInstancesByName()
				
                
 				symbolInstance.getSymbolInstancesByName()
				
                
 				symbolInstance.symbolName()
				
                
 				symbolInstance.element()
				
                
 				symbolInstance.startTimelineNamed()
				
                
 				symbolInstance.pauseTimelineNamed()
				
                
                        symbolInstance.continueTimelineNamed()
                        <key>heading</key>
                        symbolInstance.continueTimelineNamed(timelineName, direction, canRestartTimeline)
                        <key>description</key>
                        Continues the specified timeline where it left off for the symbol. Note: timelines are user-defined, so they are not enforced to be unique. If you are going to use this function, be sure that no two timelines in the symbol have the same name!&lt;br&gt;&lt;br&gt;By default continue will not start the timeline over if it is at the end, to change this behavior pass true for canRestartTimeline.&lt;br&gt;&lt;br&gt;Direction to play timeline:	&lt;div class=&quot;constants&quot;&gt;hypeDocument.kDirectionForward&lt;br&gt;hypeDocument.kDirectionReverse
                        <key>codeInsertion</key>
                        symbolInstance.continueTimelineNamed(&apos;timelineName&apos;, hypeDocument.kDirectionForward, false)
                        <key>moreInfoUrlPath</key>
                        #continueTimelineNamedSymbol
                    </dict>
                    <dict>
                        <key>title</key>
                        symbolInstance.goToTimeInTimelineNamed()
                        <key>heading</key>
                        symbolInstance.goToTimeInTimelineNamed(timeInSeconds, timelineName)
                        <key>description</key>
                        Jumps to a specific time in the specified timeline for the symbol. Note: timelines are user-defined, so they are not enforced to be unique. If you are going to use this function, be sure that no two timelines in the symbol have the same name!
                        <key>codeInsertion</key>
                        symbolInstance.goToTimeInTimelineNamed(0, &apos;timelineName&apos;)
                        <key>moreInfoUrlPath</key>
                        #goToTimeInTimelineNamedSymbol
                    </dict>
                    <dict>
                        <key>title</key>
                        symbolInstance.currentTimeInTimelineNamed()
                        <key>heading</key>
                        symbolInstance.currentTimeInTimelineNamed(timelineName)
                        <key>description</key>
                        Returns the current time of the specified timeline in seconds.
                        <key>codeInsertion</key>
                        symbolInstance.currentTimeInTimelineNamed(&apos;timelineName&apos;)
                        <key>moreInfoUrlPath</key>
                        #currentTimeInTimelineNamedSymbol
                    </dict>
                    <dict>
                        <key>title</key>
                        symbolInstance.durationForTimelineNamed()
                        <key>heading</key>
                        symbolInstance.durationForTimelineNamed(timelineName)
                        <key>description</key>
                        Returns the duration of the specified timeline in seconds.
                        <key>codeInsertion</key>
                        symbolInstance.durationForTimelineNamed(&apos;timelineName&apos;)
                        <key>moreInfoUrlPath</key>
                        #durationForTimelineNamedSymbol
                    </dict>
                    <dict>
                        <key>title</key>
                        symbolInstance.currentDirectionForTimelineNamed()
                        <key>heading</key>
                        symbolInstance.currentDirectionForTimelineNamed(timelineName)
                        <key>description</key>
                        Returns the playback direction of the specified timeline.
        &lt;br&gt;&lt;br&gt;Possible return values:	&lt;div class=&quot;constants&quot;&gt;hypeDocument.kDirectionForward&lt;br&gt;hypeDocument.kDirectionReverse
                        <key>codeInsertion</key>
                        symbolInstance.currentDirectionForTimelineNamed(&apos;timelineName&apos;)
                        <key>moreInfoUrlPath</key>
                        #currentDirectionForTimelineNamedSymbol
                    </dict>
                    <dict>
                        <key>title</key>
                        symbolInstance.isPlayingTimelineNamed()
                        <key>heading</key>
                        symbolInstance.isPlayingTimelineNamed(timelineName)
                        <key>description</key>
                        Returns true if the timeline is playing and false if it is not.
                        <key>codeInsertion</key>
                        symbolInstance.isPlayingTimelineNamed(&apos;timelineName&apos;)
                        <key>moreInfoUrlPath</key>
                        #isPlayingTimelineNamedSymbol
                    </dict>
                </array>
                <key>proOnly</key>
                <true/>
            </dict>
            <dict>
                <key>CategoryName</key>
                Drag Events
                <key>items</key>
                <array>
                    <dict>
                        <key>title</key>
                        event[&apos;hypeGesturePhase&apos;]
                        <key>heading</key>
                        event[&apos;hypeGesturePhase&apos;]
                        <key>description</key>
                        When receiving a callback for the &quot;On Drag&quot; event with the &quot;Run JavaScript…&quot; action the event object also offers information about whether the current drag gesture has just started or ended, was canceled, or the coordinates were updated. To get that state, access the hypeGesturePhase property in the event object:
        &lt;div class=&quot;constants&quot;&gt;hypeDocument.kHypeGesturePhaseStart&lt;br&gt;hypeDocument.kHypeGesturePhaseMove&lt;br&gt;hypeDocument.kHypeGesturePhaseEnd&lt;br&gt;hypeDocument.kHypeGesturePhaseCancel&lt;/div&gt;
                        <key>moreInfoUrlPath</key>
                        #hypegesturephase
                    </dict>
                    <dict>
                        <key>title</key>
                        event[&apos;hypeGestureXPosition&apos;]
                        <key>heading</key>
                        event[&apos;hypeGestureXPosition&apos;]
                        <key>description</key>
                        Returns the current x position of a drag when using the &quot;On Drag&quot; event with the &quot;Run JavaScript…&quot; action.
                        <key>moreInfoUrlPath</key>
                        #hypegesturexposition
                    </dict>
                    <dict>
                        <key>title</key>
                        event[&apos;hypeGestureYPosition&apos;]
                        <key>heading</key>
                        event[&apos;hypeGestureYPosition&apos;]
                        <key>description</key>
                        Returns the current y position of a drag when using the &quot;On Drag&quot; event with the &quot;Run JavaScript…&quot; action.
                        <key>moreInfoUrlPath</key>
                        #hypegestureyposition
                    </dict>
                </array>
            </dict>
        </array>
        </plist>
