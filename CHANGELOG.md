# inc-design-system

## 1.4.1

### Patch Changes

- style: change MultiSelect dropdown background colour
- refactor: change Modal and AlertModal components usage. Added ModalTitle and AlertModalTitle components for better user experience and customisability with the Modal and AlertModal components

## 1.4.0

### Minor Changes

- feat: add Sheet component and its sub-components. This includes Sheet, SheetPortal, SheetOverlay, SheetTrigger, SheetClose and SheetContent

## 1.3.0

### Minor Changes

- feat: add Toast component

## 1.2.4

### Patch Changes

- fix: remove unused headers prop for accordion component which caused typescript error

## 1.2.3

### Patch Changes

- feat: export all Accordion related sub-components. This includes Accordion, AccordionContent, AccordionItem and AccordionTrigger.

## 1.2.2

### Patch Changes

- feat: Usage of Accodion has changed such that each item needs to be enclosed by an accordionItem. Now, users do not need to pass in any headers props etc. Accordian children will be displayed using AccordianItem.

## 1.2.1

### Patch Changes

- style: update TableHead component height and padding. Original height and padding for TableHead was too much, making it look less appealing. Change height from 48px to 10px. Change padding from 16px for each horizontal side to 8px for each horizontal side

## 1.2.0

### Minor Changes

- feat: add Table components and its sub-components to the INC Design System Component Library. This includes Table, TableHeader, TableBody, TableFooter, TableHead, TableRow, TableCell and TableCaption

## 1.1.0

### Minor Changes

- add Avatar component and correct the issue where drag and drop did not work for the FileUpload component

## 1.0.4

### Patch Changes

- fix: correct TimePicker folder and file names to match export path to fix "Module not found: Can't resolve 'inc-design-system/timePicker'" build error

## 1.0.3

### Patch Changes

- correct typo in file paths for Modal component in package.json to fix "Module not found: Can't resolve 'inc-design-system/modal'" build error

## 1.0.2

### Patch Changes

- move all of Modal exports to last line below to fix "Module not found: Can't resolve 'inc-design-system/modal'" build error

## 1.0.0

### Major Changes

- INC DESIGN SYSTEM RELEASE!!!
