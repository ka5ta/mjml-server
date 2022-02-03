# <img src="https://i.ibb.co/cLHNZbr/drawing-logo.png" width="40" height="40" /> Driver Subscription - Part 1
Project cloned from [Siepomaga/mjml-server](https://github.com/Siepomaga/mjml-server) </br>
Microservice. Server used to render mjml code into html string

# Run

```
$ mjml-server
```

# Example request

```
$ http://127.0.0.1:1410
```
- Content-type: **application/x-www-form-urlencoded**</br>
- Body: 
  - Key:
```
mjml
```
  - Value:
```
<mjml>
  <mj-body>
    <mj-section>
      <mj-column>

        <mj-image width="100px" src="/assets/img/logo-small.png"></mj-image>

        <mj-divider border-color="#F45E43"></mj-divider>

        <mj-text font-size="20px" color="#F45E43" font-family="helvetica">Hello World</mj-text>

      </mj-column>
    </mj-section>
  </mj-body>
</mjml>
```


