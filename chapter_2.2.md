## 2.2 useEffect

- useEffect
	- A state depending on a changing state
	- Dependency array
		- No array - executes on each re-render
		- Empty - only on initial render and on last unmount
		- Values - dependencies that trigger useEffect
		 - useMemo/useCallback for referential integrity (explain === for objects)
 - Unidirectional data flow
 
 ![[assets/data_binding.png|150]]