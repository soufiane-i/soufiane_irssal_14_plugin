# Modal Confirmation

Modal confirmation that you can call it to appear.
A click in the cross button hide it.

## How To install

    npm i soufiane.irssal_plugin
    or yarn add soufiane.irssal_plugin

## How to import

    import { ModalPlugin } from "soufiane.irssal_plugin";

## Example

```
function HomePage() {
  return (
    <>
      <Header />
      <Nav
        refLink="employee-list"
        text="View Current Employees"
        arrowDirection="right"
      />
      <main>
        <CreateEmployeeForm />
      </main>
      <ModalPlugin />
    </>
  );
}

export default HomePage;

```
