---
title: DOME Issuer
---

{{< blocks/cover title="Welcome to the DOME Issuer for LEARCredentials" image_anchor="bottom" height="min" >}}
<a class="btn btn-lg btn-primary me-3 mb-4" href="/docs/">
  Learn More <i class="fas fa-arrow-alt-circle-right ms-2"></i>
</a>
<p class="lead mt-5">Scroll to see more</p>
{{< blocks/link-down color="info" >}}
{{< /blocks/cover >}}


{{% blocks/section color="light" %}}
This site is intended for Legal Representatives of companies who want to issue one or more LEARCredentials to one or more employees of the company. A LEARCredential is a type of Verifiable Credential which enables an employee, nominated by a legal representative, to act on behalf of an organisation with restricted powers with respect to third-parties.
{ .h3 }

- The issuer of the LEARCredential **must be a legal representative** of the company. The legal representative will sign the LEARCredential with an eIDAS digital certificate, which can be either a personal one or a certificate of representation.
- The receiver of the LEARCredential (both the subject and holder of the credential) **can be any employee (or contractor)** of the company. The legal representative will delegate a restricted set of powers to that person. Those restricted powers are included inside the credential and can be verified by any Relying party to whom the holder presents the LEARCredential.
{ .h3 }
{{% /blocks/section %}}


{{% blocks/lead color="primary" %}}

You must be a legal representative of the company, to be able to delegate the restricted powers required for DOME.

You need an eIDAS certificate to be able to use the system. In addition you will have to register your company email.

<a class="btn btn-lg btn-secondary me-3 mb-4" target="_blank" href="https://issuersec.mycredential.eu">
  Login as Legal Representative
</a>

{{% /blocks/lead %}}



<section style="padding-bottom: 0px;" class="row td-box td-box--white">
  <div class="col">
    <div class="row justify-content-center">
      <div class="col-lg-6 mb-5 mb-lg-0 text-center">
        <h3>In addition, you can obtain the DOME Wallet to store the credentials, and test them to authenticate to a test Verifier (acting as Relying Party).</h3>
    </div>
  </div>
</section>


<section class="row td-box td-box--white td-box--height-auto">
  <div class="col">
    <div class="row justify-content-center">
      <div class="col-lg-4 mb-5 mb-lg-0 text-center">
        <div class="mb-4 h1">
          <i class="fas fa-solid fa-wallet"></i>
        </div>
        <h4 class="h3">Obtain your wallet</h4>
        <div class="mb-0">
          <p>You need a wallet to store your LEARCredentials and present them to Relaying parties like DOME Marketplace.</p>
          <p>DOME provides a simple wallet enough for authenticating to the DOME Marketplace and performing all needed processes.</p>
          <img src="data:data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQAAAAEAAQMAAABmvDolAAAABlBMVEX///8AAABVwtN+AAABoElEQVR42uyYPXKEMAyFn4eCkiNwFI5mH81H4QiUFIxf5snALhvSZtYaVGSC8jWR9fMkPPbYY19rA2UrpmQfOb5croAZQLcOTIFcRqaw7i5nwMQigMJmRAHmcgnkyA3Y4+AWwJTCpqwGnQJ7CsfjA7dp3zpQG9KQY9j6ZczK6rsm1jhwcqmgJwX8MXiaBo5WnLEXL3rOsEpuCWD9E6IecCSLYd4AYGKgnrF0PF7TtIIrQKOyAEM+uk6gKtQdIH3X1Tis+0BhvnRaF8AMWPNJBcCYo7XZFOgLUFabFtCjo45PuS5p3z4gyWP6R21JQanPfZVJ7QP2r3dcJupXaVouZ1D8AMNcN80MLWKYpIjI9L5vugBqpQ4ZpdLFsvqiaT0A81mp5ovlCI03IJl0B6QDq5j4zIevB17KnFuvpDUVxDvp3jJwLlVV+Exp35q9AfuKLJ/tWaya9tda3Tpw3EBKJzULiws/itcNgGgDBbH0+vm+kHoCbJJI/4QaCHfAeb7qFAcUO/jcHO7aBo6LlsmDuqjUG4Ir4LHHHvt3+wkAAP//DQRXndz8xuAAAAAASUVORK5CYII=" alt="EvidenceLedger logo">
          <h4>Scan this QR code or go in your mobile to <a target="_blank" href="https://wallet.mycredential.eu"><b>wallet.mycredential.eu</b></a></h4>
        </div>
      </div>
      <div class="col-lg-4 mb-5 mb-lg-0 text-center">
        <div class="mb-4 h1">
          <i class="fas fa-solid fa-check"></i>
        </div>
        <h4 class="h3">Test the credential with a Verifier</h4>
        <div class="mb-0">
          <p>Use your LEARCredential in your wallet to authenticate to a test Verifier, without user or password.</p>
          <p>In this way you can see how everything works and will become familiar with the flows.</p>
          <a class="btn btn-lg btn-primary me-3 mb-4" target="_blank" href="https://verifier.mycredential.eu/verifier">
            Go to the test Verifier
          </a>
        </div>
      </div>
    </div>
  </div>
</section>
