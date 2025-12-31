## TC-SEARCH-001

**Title:** Search for an existing product the search bar

**Preconditions:**
- User is on Mercado Libre home page
- Use has internet connection

**Steps:**
1. Locate the search bar
2. Type "audifonos"
3. Press Enter

**Expect Result:**
- The system displays a list of products related to the searched term

### TC-SEARCH-002

**Title:** Display autocomplete suggestions while typing in the search bar

**Preconditions:**
- User is on Mercado Libre home page

**Steps:**
1. Click on the search bar
2. Type "aud"

**Expected Result:**
- Autocomplete suggestions are displayed below the search bar

### TC-SEARCH-003

**Title:** Display filters on search results page

**Preconditions:**
- User has searched for a product

**Steps:**
1. Perform a product search
2. Observe the left side of the results page

**Expected Result:**
- Filters are displayed to refine search results

  ## Test Coverage Decision
Three test cases were designed for this feature since the search functionality is low in complexity and can be classified as smoke testing. It does not involve financial transactions or sensitive personal data, therefore the associated business risk is low.


## Test Execution
### TC-SEARCH-001

**Status:** Pass

**Actual Result:**
- The system displayed a list of products related to the searched term.

**Execution Notes:**
- Results loaded correctly without noticeable delay.

  ### TC-SEARCH-002

**Status:** Pass

**Actual Result:**
- Autocomplete suggestions were displayed while typing.

**Execution Notes:**
- Suggestions appeared after typing the first three characters.


### TC-SEARCH-003

**Status:** Pass 

**Actual Result:**
- Filters were displayed on the left side of the results page.

**Execution Notes:**
- The "Category" filter displays general store categories instead of product-specific categories.
- This behavior may cause confusion for users searching for a specific product, as the filter is not directly related to the searched item.
- When additional product filters are applied, the product list updates correctly and shows relevant results.



