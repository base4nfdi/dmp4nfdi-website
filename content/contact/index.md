---
title: Contact
date: 2024-07-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Questions? Suggestions? Something else? We're always glad to hear from you. Drop us a line and we'll respond as soon as possible.

        <!-- Put form here as HTML, because the hugo template does not support custom URLs for contact forms.. -->

        <div class="mb-3">
         <form action="https://dmp.nfdiform.techfak.de/create" method="post">
          <div class="container mt-5">
            <div class="form-group row">
              <label for="subject" class="col-sm-2 col-form-label">Subject:</label>
              <input required type="text" id="subject" name="subject" class="form-control col-sm-10" placeholder="Enter subject">
            </div>
            <div class="form-group row">
              <label for="requester" class="col-sm-2 col-form-label">Your name:</label>
              <input required type="text" id="requester" name="requester" class="form-control col-sm-10" placeholder="Enter your name">
            </div>
            <div class="form-group row">
              <label for="affiliation" class="col-sm-2 col-form-label">Your affiliation (Consortium / Institution):</label>
              <input required type="text" id="affiliation" name="affiliation" class="form-control col-sm-10" placeholder="Enter your affiliation">
            </div>
            <div class="form-group row">
              <label for="mail" class="col-sm-2 col-form-label">Your contact mail:</label>
              <input required type="email" id="mail" name="mail" class="form-control col-sm-10" placeholder="Enter your e-mail">
            </div>
            <div class="form-group row">
              <label for="description" class="col-sm-2 col-form-label">Detailed description of your enquiry:</label>
              <textarea id="description" name="description" class="form-control col-sm-10" rows="3"></textarea>
            </div>
              <div class="form-group row" style="display: none;">
                  <label for="bl4nk" class="col-sm-2 col-form-label">Bot check:</label>
                  <input type="text" id="bl4nk" name="bl4nk" class="form-control col-sm-10" placeholder="">
              </div>
            <button type="submit" class="btn btn-primary col-sm-2 offset-sm-5">Create Ticket</button>
          </div>
        </form> 
        </div>

        Or contact us by email:

      email: dmp4nfdi<-@->lists.nfdi.de
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: false

    design:
      columns: '1'
---
