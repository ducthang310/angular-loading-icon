# angular-loading-icon
Loading icon

### How to use
Import the loading component into `app.module.ts`

```
@NgModule({
  declarations: [
    ...,
    LoadingComponent
  ]
})
```

In template files: 
```

<app-loading></app-loading>

<div class="loading-container">
  <app-loading></app-loading>
</div>

<button type="button" class="btn btn-primary btn-loading-s" disabled>
  <span class="txt-loading">Apply</span>
  <app-loading></app-loading>
</button>

```
