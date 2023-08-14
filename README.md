# goit-markup-hw-02

.header {
padding-top: 24px;
padding-bottom: 24px;
border-bottom: 1px solid var(--cornflower);
box-shadow: 0px 1px 6px 0px rgba(46, 47, 66, 0.08),
0px 1px 1px 0px rgba(46, 47, 66, 0.16),
0px 2px 1px 0px rgba(46, 47, 66, 0.08);
}
.header-container {
display: flex;
align-items: center;
}
.header-navigation {
display: flex;
align-items: center;
gap: 76px;
}
.header-logo {
color: var(--iris);
font-family: "Raleway", sans-serif;
font-size: 18px;
font-weight: 800;
line-height: 1.17;
letter-spacing: 0.03em;
text-transform: uppercase;
}
.header-logo-color {
font-family: var(--pramiry-font);
color: var(--navy-blue);
font-size: 18px;
font-weight: 800;
line-height: 1.16;
letter-spacing: 0.03em;
}
.header-navigation-list {
display: flex;
gap: 40px;
}
.header-navigation-item {
}
.header-link {
padding: 24px 0;
position: relative;
color: var(--navy-blue);
font-family: Roboto;
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
transition: color var(--hover-transition);
}

.current-page {
color: var(--ocean);
}

.current-page::after {
content: "";
position: absolute;
left: 0;
bottom: -1px;
width: 100%;
height: 4px;
display: block;
background-color: var(--ocean);
border-radius: 2px;
}

.header-address {
font-style: normal;
margin-left: auto;
}
.header-address-list {
display: flex;
gap: 40px;
}
.header-address-item {
color: var(--slate);
font-family: Roboto;
font-size: 16px;
font-style: normal;
line-height: 1.5;
letter-spacing: 0.02em;
}
.header-address-link {
transition: color var(--hover-transition);
}

/_ Main styles --------------------------------------------------------------- _/

.main {
}

/_ Hero ---------------------------------------------------------------_/

.hero {
max-width: 1440px;
background: var(--navy-blue);
background-image: linear-gradient(
rgba(46, 47, 66, 0.7),
rgba(46, 47, 66, 0.7)
),
url(../images/people-office-hero.jpg);
background-repeat: no-repeat;
background-position: center;
background-size: cover;
padding: 188px 0;
margin: 0 auto;
}
.container-hero {
display: flex;
flex-direction: column;
align-items: center;
gap: 48px;
}
.hero-title {
color: var(--white);
text-align: center;
font-family: var(--pramiry-font);
font-size: 56px;
line-height: 1.07;
letter-spacing: 0.02em;
max-width: 496px;
height: 120px;
}
.hero-button {
color: var(--white);
background: var(--iris);
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
cursor: pointer;
border: none;
display: block;
min-width: 169px;
height: 56px;
padding: 16px 32px;
border-radius: 4px;
box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.15);
transition: background-color var(--hover-transition);
}

/_Adventages ---------------------------------------------------------------_/

.advantages {
padding: 120px 0;
}
.advantages-list {
display: flex;
gap: 24px;
}
.advantages-list-item {
width: calc((100% - 72px) / 4);
}
.advantages-item-title {
color: var(--navy-blue);
font-family: var(--pramiry-font);
font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;
margin-bottom: 8px;
}
.advantages-item-text {
color: var(--slate);
font-family: var(--pramiry-font);
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
}

.advantages-item-top {
width: 100%;
height: 112px;
display: flex;
align-items: center;
justify-content: center;
border-radius: 4px;
background-color: var(--cloud, #f4f4fd);
margin-bottom: 8px;
}

.advantages-icons {
}

/_ Examples --------------------------------------------------------------- _/

.examples {
padding-bottom: 120px;
}
.container-examples {
}
.examples-title {
color: var(--navy-blue);
text-align: center;
font-family: var(--pramiry-font);
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
margin-bottom: 72px;
}
.examples-list {
display: flex;
gap: 24px;
}
.examples-list-item {
width: calc((100% - 48px) / 3);
}
.examples-list-img {
}

/_ Team --------------------------------------------------------------- _/

.team {
background-color: var(--cloud);
padding: 120px 0;
}
.container-team {
}
.team-title {
color: var(--navy-blue);
text-align: center;
font-family: var(--pramiry-font);
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
margin-bottom: 72px;
}
.team-list {
display: flex;
gap: 24px;
}
.team-list-item {
background-color: var(--white);
width: calc((100% - 72px) / 4);
border-radius: 0px 0px 4px 4px;
box-shadow: 0px 2px 1px 0px rgba(46, 47, 66, 0.08),
0px 1px 1px 0px rgba(46, 47, 66, 0.16),
0px 1px 6px 0px rgba(46, 47, 66, 0.08);
}
.team-list-img {
}
.team-list-title {
color: var(--navy-blue);
text-align: center;
font-family: var(--pramiry-font);
font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;
margin-bottom: 8px;
}
.team-list-text {
color: var(--slate);
text-align: center;
font-family: var(--pramiry-font);
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
}
.team-list-content {
padding: 32px 0;
}

.team-list-icon {
display: flex;
gap: 24px;
justify-content: center;
margin-top: 8px;
}

.team-item-icon {
width: 40px;
height: 40px;
}

.team-list-link {
width: 100%;
height: 100%;
background-color: var(--iris);
border-radius: 50%;
display: flex;
align-items: center;
justify-content: center;
transition: background-color var(--hover-transition);
}

.team-list-link:hover,
.team-list-link:focus {
background-color: var(--ocean, #404bbf);
}

.team-link-icon {
fill: var(--cloud);
}

/_ Customers ------------------------------------------------------------- _/

.customers {
padding-top: 120px;
padding-bottom: 120px;
}
.customers-title {
font-family: var(--pramiry-font);
font-size: 36px;
font-weight: 700;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
text-align: center;
color: var(--navy-blue);
margin-bottom: 72px;
}
.customers-list {
display: flex;
gap: 24px;
}
.customers-item {
width: calc((100% - 120px) / 6);
height: 88px;
}
.customers-link {
width: 100%;
height: 100%;
border-radius: 4px;
border: 1px solid var(--light-slate, #8e8f99);
display: flex;
align-items: center;
justify-content: center;
color: var(--light-slate);
transition: border-color var(--hover-transition),
color var(--hover-transition);
}
.customers-link:hover,
.customers-link:focus {
color: var(--ocean);
border-color: var(--ocean);
}
.customers-icons {
fill: currentColor;
}

/_ Footer --------------------------------------------------------------- _/

.footer {
background: var(--navy-blue);
padding: 100px 0;
display: flex;
}

.footer-flex {
display: flex;
align-items: baseline;
}
.container-footer {
margin-right: 120px;
}
.footer-text {
color: var(--cloud);
font-family: var(--pramiry-font);
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
max-width: 264px;
max-height: 72px;
}
.footer-logo {
color: var(--iris);
font-family: "Raleway", sans-serif;
font-size: 18px;
font-weight: 800;
line-height: 1.17;
letter-spacing: 0.03em;
text-transform: uppercase;
display: inline-block;
margin-bottom: 16px;
}
.footer-logo-color {
color: var(--cloud, #f4f4fd);
font-family: "Raleway", sans-serif;
font-size: 18px;
font-weight: 800;
line-height: 1.17;
letter-spacing: 0.03em;
text-transform: uppercase;
}

.container-footer-icon {
}

.footer-icon-title {
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--white, #fff);
margin-bottom: 16px;
}

.footer-list-icon {
display: flex;
width: 208px;
height: 40px;
gap: 16px;
}

.footer-item-icon {
width: 40px;
height: 40px;
}

.footer-list-link {
width: 100%;
height: 100%;
background-color: var(--iris);
border-radius: 50%;
display: flex;
align-items: center;
justify-content: center;
transition: background-color var(--hover-transition);
}

.footer-list-link:hover,
.footer-list-link:focus {
background-color: var(--green, #31d0aa);
}
.footer-link-icon {
fill: var(--cloud);
}

.container-footer-form {
margin-left: 80px;
}

.footer-form-title {
color: var(--white, #fff);
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
margin-bottom: 16px;
}

.footer-form {
display: flex;
gap: 24px;
}

.footer-form-label {
}

.footer-input {
width: 264px;
height: 40px;
padding: 8px 16px;
border-radius: 4px;
border: 1px solid var(--white, #fff);
box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.15);
filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
background-color: transparent;
outline: transparent;
color: var(--white, #fff);
font-family: var(--pramiry-font);
font-size: 12px;
line-height: 1.5;
letter-spacing: 0.04em;
transition: border-color var(--hover-transition);
}

.footer-input::placeholder {
color: var(--white, #fff);
font-family: var(--pramiry-font);
font-size: 12px;
line-height: 2;
letter-spacing: 0.04em;
transition: color var(--hover-transition);
}

.footer-input:hover,
.footer-input:focus {
border-color: var(--iris);
}

.footer-input:hover::placeholder {
color: var(--iris);
}

.subscribe-btn {
border-radius: 4px;
color: var(--white);
background-color: var(--iris, #4d5ae5);
min-width: 165px;
height: 40px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
cursor: pointer;
border: none;
display: flex;
padding: 8px 24px;
justify-content: center;
align-items: center;
transition: background-color var(--hover-transition);
}

.subscribe-btn-icon {
fill: var(--white);
margin-left: 16px;
}

/_ Portfolio ---------------------------------------------------------------_/

.portfolio {
padding-top: 96px;
padding-bottom: 120px;
}
.portfolio-filter-list {
display: flex;
margin-bottom: 72px;
justify-content: center;
gap: 24px;
}
.portfolio-filter-item {
}
.portfolio-filter-button {
color: var(--iris);
background: var(--cloud);
text-align: center;
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
cursor: pointer;
border-radius: 4px;
border: 1px solid var(--cornflower, #e7e9fc);
padding: 12px 24px 12px 24px;
transition: background-color var(--hover-transition),
color var(--hover-transition), border-color var(--hover-transition),
box-shadow var(--hover-transition);
}
.portfolio-btn:hover,
.portfolio-btn:focus {
border: 1px solid transparent;
box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 2px 1px rgba(0, 0, 0, 0.08),
0px 2px 2px rgba(0, 0, 0, 0.12);
}
.portfolio-list {
display: flex;
flex-wrap: wrap;
gap: 48px 24px;
}
.portfolio-list-item {
width: calc((100% - 48px) / 3);
}

.portfolio-cover-wrap {
position: relative;
overflow: hidden;
}

.portfolio-list-img {
}
.portfolio-cover-text {
font-family: var(--pramiry-font);
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--cloud);
position: absolute;
top: 0;
background: var(--iris, #4d5ae5);
height: 100%;
padding: 40px 32px;
transform: translateY(100%);
transition: transform var(--hover-transition);
}

.portfolio-img-link {
display: block;
transition: box-shadow var(--hover-transition);
}

.portfolio-img-link:hover,
.portfolio-img-link:focus {
box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
}

.portfolio-img-link:hover .portfolio-cover-text {
transform: translateY(0);
}

.portfolio-img-link:focus .portfolio-cover-text {
transform: translateY(0);
}

.portfolio-item-content {
padding: 32px 16px;
border: 1px solid var(--cornflower);
border-top: none;
}

.portfolio-list-title {
color: var(--navy-blue);
font-family: var(--pramiry-font);
font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;
margin-bottom: 8px;
}
.portfolio-list-text {
color: var(--slate);
font-family: var(--pramiry-font);
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
}

/_ Modal ------------------------------------------------------------------- _/

.backdrop {
position: fixed;
width: 100%;
height: 100%;
background: var(--navyblue-modal, rgba(46, 47, 66, 0.4));
top: 0;
transition: opacity var(--hover-transition),
visibility var(--hover-transition);
}

.modal {
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%) scale(1);
width: 408px;
min-height: 584px;
border-radius: 4px;
background-color: var(--dairy, #fcfcfc);
box-shadow: 0px 2px 1px 0px rgba(0, 0, 0, 0.2),
0px 1px 3px 0px rgba(0, 0, 0, 0.12), 0px 1px 1px 0px rgba(0, 0, 0, 0.14);
transition: transform var(--hover-transition);
padding: 72px 24px 24px 24px;
}
.backdrop.is-hidden .modal {
transform: translate(-50%, -50%) scale(0);
}

.modal-close-btn {
position: absolute;
top: 24px;
right: 24px;
cursor: pointer;
width: 24px;
height: 24px;
padding: 0;
display: flex;
align-items: center;
justify-content: center;
background-color: var(--cornflower);
border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%;
transition: background-color var(--hover-transition),
border var(--hover-transition);
}

.modal-close-btn:hover,
.modal-close-btn:focus {
background-color: var(--ocean);
border: none;
}

.modal-close-btn:hover .modal-close-svg {
fill: var(--white);
transition: fill var(--hover-transition);
}

.modal-close-btn:focus .modal-close-svg {
fill: var(--white);
transition: fill var(--hover-transition);
}

.modal-close-svg {
fill: var(--navy-blue);
}

.modal-title {
color: var(--navy-blue, #2e2f42);
text-align: center;
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
margin-bottom: 16px;
}
.modal-form {
}

.modal-field {
margin-bottom: 8px;
}

.modal-input {
width: 100%;
height: 40px;
background-color: transparent;
border-radius: 4px;
border: 1px solid var(--navy-blue-modal, rgba(46, 47, 66, 0.4));
padding-left: 38px;
padding-right: 16px;
outline: transparent;
transition: border-color var(--hover-transition);
}

.modal-input:hover,
.modal-input:focus {
border-color: var(--iris);
}

.modal-label {
display: inline-block;
color: var(--light-slate, #8e8f99);
font-family: var(--pramiry-font);
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
margin-bottom: 4px;
display: block;
}

.modal-field-comment {
margin-bottom: 16px;
}

.modal-input-wrap {
position: relative;
}

.modal-icons {
fill: var(--navy-blue);
position: absolute;
left: 16px;
top: 50%;
transform: translateY(-50%);
transition: fill var(--hover-transition);
}

.modal-input:hover + .modal-icons,
.modal-input:focus + .modal-icons {
fill: var(--iris);
}

.modal-input-btn {
color: var(--white);
background: var(--iris);
font-family: var(--pramiry-font);
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
cursor: pointer;
border: none;
display: block;
min-width: 169px;
height: 56px;
padding: 16px 32px;
border-radius: 4px;
box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.15);
transition: background-color var(--hover-transition);
margin: 0 auto;
}

.modal-comment {
width: 100%;
height: 120px;
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: var(--navy-blue);
background-color: transparent;
border-radius: 4px;
border: 1px solid var(--navy-blue-modal, rgba(46, 47, 66, 0.4));
padding: 8px 16px;
outline: transparent;
transition: border-color var(--hover-transition);
resize: none;
}

.modal-comment::placeholder {
color: var(--navy-blue-modal, rgba(46, 47, 66, 0.4));
font-family: var(--pramiry-font);
font-size: 12px;
line-height: 1.2;
letter-spacing: 0.04em;
transition: color var(--hover-transition);
}

.modal-comment:hover,
.modal-comment:focus {
border-color: var(--iris);
}

.modal-comment:hover::placeholder {
color: var(--iris);
}

.modal-field-checkbox {
margin-bottom: 24px;
}

.modal-check {
}

.modal-check-text {
color: var(--light-slate, #8e8f99);
font-family: var(--pramiry-font);
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
}

.modal-check-span {
width: 16px;
height: 16px;
border: 1px solid rgba(46, 47, 66, 0.4);
border-radius: 2px;
display: inline-flex;
align-items: center;
justify-content: center;
margin-right: 8px;
fill: transparent;
transition: background-color var(--hover-transition),
border var(--hover-transition), fill var(--hover-transition);
}

.modal-check:checked + .modal-check-text span {
background-color: var(--ocean);
border: none;
fill: var(--cloud);
}

.modal-check-link {
color: var(--iris, #4d5ae5);
}

.is-hidden {
opacity: 0;
visibility: hidden;
pointer-events: none;
}
